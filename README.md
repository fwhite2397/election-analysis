# Overview of Election Audit
The voting commission has requested an audit of the previous election containing the following information regarding the results:
* Total number of votes
* Percentage and number of votes per county
* County with largest number of votes
* Percentage and number of votes per candidate
* Winning candidate:
  * Name
  * Number of votes
  * Percentage of votes

We have been tasked with writing code that will provide the requested information to the voting commission via a text file containing the results.


# Election-Audit Results: 
Here are the results that will be recorded in the result files:
![image](https://user-images.githubusercontent.com/95976771/147859048-5dbee0ca-26bb-480c-97c6-de12996ad4f6.png)

The image above answers the following questions the voting comission had about the election:
* How many votes were cast in this congressional election?
  * There were 369,711  total votes
* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  * Jefferson County: 10.5% (38,855 votes)
  * Denver County: 82.8% (306,055 votes)
  * Arapahoe County: 6.7% (23,801 votes)
* Which county had the largest number of votes?
  * Denver County had the largest number of votes with 306, 055, which accounted vor 82.8% of the votes
* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  * Charles Casper Stockham: 23.0% (85,123 votes)
  * Diana DeGette: 73.8% (272,892 votes)
  * Raymon Anthony Doane: 3.1% (11,606 votes)
* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  * Winner: Diana DeGette
  * Winning Vote Count: 272,892
  * Winning Percentage: 73.8%


# Election-Audit Summary: 
Using Python, we were able to read the ata contained in the election_results.csv file and provide useful information to the voting commission. 
The information we were able to derive were the total number of votes, vote counts and percentages by county, candidates, and the winner. 
This information obtained was written to an output file that will be used to show the voting commission the final results of our analysis.
The finalized results show that Denver county had the most votes and the winner of the election was Diana DeGette.

