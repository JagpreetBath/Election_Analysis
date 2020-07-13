# Election Audit Analysis

## Project Overview
Tom is a Colorado Board of Elections employee who is assigned by his manger to perform an election audit of the tabulated results for U.S. Congressional precinct in Colorado. Three primary voting methods are taken into account: Mail-in ballots, punch cards, and direct recording electronic or DRE counting machines. Altogether the votes cast by these three methods will determine the final election results. The purpose of this project is to help Tom to perform an election audit of the tabulated results for U.S. Congressional precinct in Colorado using python. Also, if this audit is done successfully with Python, the code will be used for senatorial districts and local elections.

## Resources 
- Data Source: election_result.csv
- Software: Python 3.7.6, Visual Studio Code, 1.47.0

## Results
The analysis of the election audit shows that:
- There were 369,711 votes cast in the congressional election.
- Breakdown of the number of votes and the percentage of total votes for each county in the precinct:
    - Jefferson county had 10.5% of the vote and 38,855 number of votes
    - Denver county had 82.8% of the vote and 306,055 number of votes
    - Arapahoe county had 6.7% of the vote and 24,801 number of votes
- Denver county had the largest number of votes. 
- Breakdown of the number of votes and the percentage of the total votes each candidate:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes
- The winner of the election was: 
    - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes

## Summary 
The script can be modified and used to analyze any elections. Following are two examples for modifying the script:
1. Change the file_to_load(the file that contains election data). Two ways to change the file are: 
    - Change the current file name with the new file name that requires analysis.
    - Add python input function that will allow the user to enter the file name and then run an analysis on the input file.
2. Update the script and add another 'for' loop. Here are two scenarios that will require the script update to add another "for' loop:
    - Perform analysis for senatorial districts and local elections
    - Perform analysis for presidential elections elections