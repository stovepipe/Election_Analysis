# PyPoll with Python

## Overview of Election Audit

    The Colorado Board of Elections has requested an election audit of the voter precinct encompassing Jefferson, Denver and Arapahoe counties. The Board is seeking to confirm the total number of votes cast, broken down by county and candidate. PyPoll_Challenge.py has been developed to aid in the election audit. Running the script will produce the output desired by the Board and possibly, serve as a functional tool for future election audits after some minor modifications.

## Election Audit Results
    
    * How many votes were cast in this congressional election?
        - 369,711 votes
    
    * Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
        - Jefferson: 10.5% (38,855)
        - Denver: 82.8% (306,055)
        - Arapahoe: 6.7% (24,801)
    
    * Which county had the largest number of votes?
        - Denver County
    
    * Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
        - Charles Casper Stockham: 23.0% (85,213)
        - Diana DeGette: 73.8% (272,892)
        - Raymon Anthony Doane: 3.1% (11,606)

    * Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
        - Winner: Diana DeGette
        - Winning Vote Count: 272,892
        - Winning Percentage: 73.8%
    
![Terminal%20Output.png](https://github.com/stovepipe/Election_Analysis/blob/main/Terminal%20Output.png)

## Election Audit Summary

    Through the course of this project, the script developed into a versatile tool that can be used for future elections with some minor modifications. I recommend the Election Commission retain this script for future analysis because of the minimal modifications to accomodate other csv files. Because we have set variables like "Candidate_Name" and "County_Name" to reference locations on a csv file, this script can be used on any csv file with the same format or headers.

![Line_DataCall_Mod.png](https://github.com/stovepipe/Election_Analysis/blob/main/Line_DataCall_Mod.png)

    Modifications to the script for other election analysis could be accomplished by manipulating lines 48 & 51 to reflect different variables based on data in fields 1 & 2. Alternatively, rather than change the variable, if the county name or candidate name are in other fields, the field index can be changed here. This is also the area where this script can be expanded to analyze additional fields by defining and mapping additional variables to a location on the csv file. 

![Line_Nine_Mod.png](https://github.com/stovepipe/Election_Analysis/blob/main/Line_Nine_Mod.png)

    Modification for additional analysis would also include modifying line 9 to read in additional csv files.