# Election_Analysis


## Overview Of Election Audit

- Two employees who work for an election commission based in Colorado requested my help analyzing some election results. They provided me with a CSV file containing:
* The ballot IDs of the voters in this election
* The county in which they voted
* The candidate whom they voted for

I was given the task of analyzing this data in order to help them find the following:
*The voter turnout for each county
*The percentage of votes from each county out of the total vote count 
*The county with the highest turnout

I was able to find all of this information using several codes that were written in the Python language.

## Election-Audit Results

### How many votes were cast in this election?

<<<<<<< HEAD
- I was able to write a python code in order to obtain this information without having to count through the extensive data one by one. What I found was that there were 369,711 votes in this election. I did this by using a For Loop to add a vote count for every row of data in our CSV file.
=======
- I was able to write a python code in order to obtain this information without having to count through the extensive data one by one. What I found was that there were 369,711 votes in this election. I did this by using a For Loop to add a vote count for every row of data in our CSV file. Below is a snippet of the code where thish his executed.
<img width="572" alt="Screen Shot 2022-03-25 at 1 17 32 PM" src="https://user-images.githubusercontent.com/100390727/160178715-4c41aa80-c090-4325-857b-11f29a7731ad.png">

### Number of Votes and Percentage of Votes for Each County

- I found the number of votes as well as the percentage of votes for the 3 counties that I was analyzing. The results are:
* Denver - 306,055 votes (%82.8)
* Jefferson - 38,855 votes (%10.5)
* Arapahoe - 24,801 votes (%6.7)

According to this data, Denver county had the highest number of votes, which is to be expected since I'm assuming its much larger than the other 2 counties. Arapahoe county had the least amount of votes.

### Number of Votes & Percentages Acquired by Candidates

- Similarily, I used Python to find information about the 3 candidates who partook in this election. I used a series of Loops and Condidionals as well as mathematic operators to obtain this information as well. Here are my results:
* Diana Degette - 272,892 votes (%73.8)
* Charles Casper Stockham - 85,213 votes (%23)
* Raymon Anthony Doane - 11,606 votes (%3.1)

As you can see, Diana Degette was the winner of this election by far.

Side note: All of this information I'm sharing has been executed with Python and written to a seperate text file named "election_results.txt" which is provided in this repository. The file's data looks like this:
<img width="572" alt="Screen Shot 2022-03-25 at 1 31 44 PM" src="https://user-images.githubusercontent.com/100390727/160180836-06fafa87-1f1b-4940-8dc6-e88dce1aac4b.png">

## Summary
Using Python, I was able to effectively help the employees of this election commision team gather the data they needed. The script I wrote could be modified and used for other elections as well. Adjusting the index numbers within our For Loops so they match the desired county, city or state of another CSV file, for instance, is a way we can repurpose this code for another election. Here is a screenshot of this occurrence in my current code: 
<img width="572" alt="Screen Shot 2022-03-25 at 1 41 56 PM" src="https://user-images.githubusercontent.com/100390727/160182311-1e8a707b-a35c-416d-9939-d9ce47e7ab9b.png">

New variables would need to be declared as well, but with just a few simple adjustments this could be a very effective script for more than just the election I analyzed.

All in all, Python is a powerful data analytics tool and it can be used for a plethora of scenarios in which we need to better understand or extract data. I'm glad that I was able to help these employees and I hope they consider my skills for future elections.


>>>>>>> 8141f2f05f88e2135dd7168732d3b29b7faa9690
