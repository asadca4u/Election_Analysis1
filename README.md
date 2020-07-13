# Election_Analysis1

## Project Overview
#### The Colorado Board of elections has requested the following analyses be done in order to complete and certify the results of the recent congressional election. 

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received a vote.
3. Calculate the total number of votes and percentage of total votes each candidate received. 
4. Determine the winner of the election based on the popular vote. 
5. Calculate the total number of votes and percentage of total votes cast in each county. 
6. Determine the county with the greatest voter turnout. 

## Election Audit Results
#### How many votes were cast in this congressional election?
- A total of 369,711 votes were cast. 
#### Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
- Three counties were analyzed: Denver, Jefferson and Arapahoe. 
  - Denver County casted 306,055 votes, which is 82.8% of the total votes cast. 
  - Jefferson County casted 38,855 votes, which is 10.5% of the total votes cast. 
  - Arapahoe County casted 24,801 votes, which is 6.7% of the total votes cast. 
#### Which county had the largest number of votes?
- Denver county had the largest number of votes cast with 82.8% of the total. 
#### Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
- Three candidates received votes in the congressional election: 
  - Charles Casper Stockham, who received 23.0% of the votes, which is 85,213 votes. 
  - Diana DeGette, who received 73.8% of the votes, which is 272,892 votes. 
  - Raymon Anthony Doane, who received 3.1% of the votes, which is 11,606 votes. 
#### Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
- Diana DeGette won the congressional election for Colorado with 272,892 votes, which represents 73.8% of the total votes cast. 


## Election Audit Summary
- The program written for this election audit is not nescessarily unique to the recent Colorado congressional election, it can be adapted to audit any election, given that the perameters of the data are formated correctly. 
- The script used simple for loops in order to run through and retrieve all the relevant data from the .csv file provided by the elections comission, with further uses of conditional statements in order to aggregate the total vote counts by the county (or any applicable region) in which they were cast and by the candidates who received them. 
- Take for example a national presidental election, which although keeps track of popular vote, is ultimately decided by seats won in the electoral college; this program may be altered to track the number of delegates won up to a threshold of 270 out of the total 538 avaliable seats. 
  - A for loop may be created that cross references the total number of seats received by each candidate from each state. 
  - A conditional statement may be created that declares a winner if the electoral seat counts reach a threshold of 270.

