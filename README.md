# Election_Analysis
Performing analysis on Election Results data to complete the audit
# Election Analysis with VS Code

## Overview of Project
Elections are highstakes for voters and requires relaible data anlysis to determine and report the winner. The available data inlcudes the voter ID, County where they reside, and the Candidate that each voter voted for. Thsi analysis is inteded to provide information about the voter turn out in each county and the counts nad percentages of votes for each candidate. 

### Purpose
In order to pronounce a winner based on the Election Results dataset, the data will be analyzed via python in VS code to provide the election commision with count and percent data. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
####Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

##### - How many votes were cast in this congressional election?
         -369711

##### - Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
        - Jefferson: 10.5% (38,855)
        - Denver: 82.8% (306,055)
        - Arapahoe: 6.7% (24,801)
##### - Which county had the largest number of votes?
        - Denver
##### - Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
        - Charles Casper Stockham: 23.0% (85,213)
        - Diana DeGette: 73.8% (272,892)
        - Raymon Anthony Doane: 3.1% (11,606)
##### - Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
        - Diana DeGette: 73.8% (272,892)
#### Challenges
I had difficulty using the with open function in VS Code on my Mac after I downloaded anacanda and pandas. I uninstalled and reinstalled VS Code and that did not help. I figured out a work around with the os.join and with open statments by putting the data ini teh same folder as the .py file and joining in that folder instead of the resource folder. 
I also struggled with the code to count counties. For some reason the same code worked on candidate but not county. 


### Election-Audit Summary: 
####In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
  This script can be used for any elections with some simple modicifations. The two main statements that would need to be modified are the read.csv and the write.csv. As long as the headers, and variables are the same then the rest of the script shold run apropriately. 
