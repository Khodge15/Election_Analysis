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

##### - Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

##### - Which county had the largest number of votes?

##### - Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

##### - Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

#### Challenges
I had difficulty using the with open function in VS Code on my Mac after I downloaded anacanda and pandas. I uninstalled and reinstalled VS Code and that did not help. I figured out a work around with the os.join and with open statments by putting the data ini teh same folder as the .py file and joining in that folder instead of the resource folder. 
I also struggled with the code to count counties. For some reason the same code worked on candidate but not county. 


### Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
