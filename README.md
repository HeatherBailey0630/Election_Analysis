# Election_Analysis
## Project Overview

Colorado Board of Elections assigned the following tasks to complete an election audit of a recent local congressional election:
1. Calculate the total number of votes cast
2. Obtain a complete list of candidates who received votes
3. Calculate the total number of votes each candidate received
4. Calculate the percentage of votes each candidate won
5. Determine the winner of the election based on popular vote

## Resources
Data Source: election_results.csv

Software: Python 3.6.1, Visual Studio Code 1.38.1

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 85,213 votes, and 23.0% of the vote.
  - Diana DeGette received 272,892 votes, and 73.8% of the vote.
  - Raymon Anthony Doane received 11,606 votes, and 3.1% of the vote.
- The winner of the election was:
  - **Diana DeGette** who received *272,892* votes and *73.8%* of the total vote.
  
  ## Challenge Overview
  
  The purpose of this challenge was to analyze the election_results.csv file in VS code. Using various methods in python, we gathered information on the candidates, counties, and votes to interpret who won the election. 
  
  ## Election-Audit Results
  - There were 369,711 total votes cast in the election
  
  Data by County
  
    - Jefferson County cast 38,855 votes, or 10.5% of the total votes
    - Denver County cast 306,055 votes, or 82.8% of the total votes
    - Arapahoe County cast 24,801 votes, or 6.7% of the total votes
    - Denver County had the largest number of votes, at 306,055 and 82.8%
    
  Data by Candidate
    
  - Charles Casper Stockham received 85,213 votes, and 23.0% of the vote.
  - Diana DeGette received 272,892 votes, and 73.8% of the vote.
  - Raymon Anthony Doane received 11,606 votes, and 3.1% of the vote.
  - The winner of the election was Diana DeGette with the highest votes at 272,892 and 73.8%


![Election_Results](https://user-images.githubusercontent.com/106620821/178171160-bc400a7c-2124-405c-93ac-3457ae8db7f1.png)
 
  
## Summary
Using python proved useful in gathering all pertinent data from the election_results.csv file and interpreting it. Using for loops, conditional statements, and dictionaries we were able to successfully obtain the accurate election results. This script could be used as is for a similar election, or modified for any election, such as local county and state elections. It could also be modified to interpret data from polls or even data from other sources, such as gathering how many views the most popular Netflix tv shows have and which show is the most "successful". Below are samples from the code pertaining to how we gathered the winner of the election and the largest county turnout. 


![py1](https://user-images.githubusercontent.com/106620821/178171397-48f638d3-0d3c-4342-abd3-9b690583654e.png)



![py2](https://user-images.githubusercontent.com/106620821/178171412-e849110b-c2d2-4b9f-ab0c-e8e53803e4f3.png)

