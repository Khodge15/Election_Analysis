# Election_Analysis
Performing analysis on Election Results data to complete the audit
# Election Analysis with VS Code

## Overview of Project
Elections are highstakes for voters and requires relaible data anlysis to determine and report the winner. The available data inlcudes the voter ID, County where they reside, and the Candidate that each voter voted for. Thsi analysis is inteded to provide information about the voter turn out in each county and the counts nad percentages of votes for each candidate. 

### Purpose
In order to pronounce a winner based on the Election Results dataset, the data will be analyzed via python in VS code to provide the election commision with count and percent data. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
#### Candidate Count and percent
For loops were used to count the total number of votes and the number of votes each candidate recieved. Then a percentage for each candidate was also calcualted.

#### County count and percentage
For loops were used to count the total number of votes and the number of votes each candidate recieved. Then a percentage for each candidate was also calcualted.

#### Challenges
I had difficulty using the with open function in VS Code on my Mac after I downloaded anacanda and pandas. I uninstalled and reinstalled VS Code and that did not help. I figured out a work around with the os.join and with open statments by putting the data ini teh same folder as the .py file and joining in that folder instead of the resource folder. 
I also struggled with the code to count counties. For some reason the same code worked on candidate but not county. 



### Outcomes
#### Text file
A text file named analysis.txt was created with all of the data output (see resource forlder). 
