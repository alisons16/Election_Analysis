# Election_Analysis
## Overview of Election Audit

### Purpose
The recent congressional election requires an audit to certify the results of the election. In this audit, we are utilizing python to count the votes to illustrate the vote breakdown (by percentage and popular vote count) among the counties and candidates. After Python counts the votes, the winner of the election is determined. With the success of this project, this Python script will be used for other election. 


## Election-Audit Results
* How many votes were cast in this congressional election?
    * There were 369,711 total votes casted in this congressional election.

* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    * Denver held 82.8% of the votes totaling 306,055 which was the most votes of the three counties in this election. Jefferson had 10.5% of the election votes totaling 38,855. Arapahoe had 6.7% of the election votes totaling 24,801.

* Which county had the largest number of votes?
    * Denver had the largest number of votes. 

* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
    * Diana DeGette had 73.8% of the votes totaling 272,892. Charles Casper Stockham had 23.0% of the votes totaling 85,213. Raymon Anthony Doane had 3.1% of the votes totaling 11,606.

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
    * Diana DeGette won the election with 73.8% of the votes totaling 272,892.

## Election-Audit Summary:
This Election-Audit Python script is not specific to this election and can be used for other elections. To use this script for other elections, two folders – named “Resources” and “analysis” - need to be added at the same level of this Python file script. Inside the Resources folder, add a CSV (named “election_results”) containing the election results. This CSV should include these headers in this order: “Ballot ID”, “County”, and “Candidate”. Starting at the second row, each row should represent one vote. The vote’s ballot ID is inputted in column A, the county in which the vote was casted is inputted in column B, and the candidate receiving the vote is inputted in Column C. 

To further develop this script, the code can be modified to verify that each column has a unique ballot ID – this would ensure that no vote is being counted twice. Another future modification could include the voting method (whether it be Mail-In Ballot, Punch Card, or Direct Recording Electronic) in Colummn D. Similar to the current script’s breakdown of votes by County, a breakdown of the number of votes and the percentage of the total votes by voting method could be printed in the terminal and the election_analysis text file. This extra data would give another level of the election count verification to strengthen the audit analysis and certification of the election results.
