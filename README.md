# Election_Analysis
Module 3: Python
## Overview of Election Audit
During this module, the Colorado Board of Elections requested an audit of a recent local congressional election that took place in Arapahoe, Denver, and Jefferson counties. In this analysis they have requested calculations for:
1. Total number of votes casted
2. Total number of votes cast in each county & percent of the total vote count
3. The county with the highest voter turnout
4. Total number of votes casted by each candidate & percent of the total vote count
5. And finally, the winner of the election

## Election Audit Results
Now let's address the requested calculations. 
* The candidates running in this election were:
  * Diana DeGette
  * Raymon Anthony Doane
  * Charles Casper Stockham
* There were a total of 369,711 votes casted in the election.
* Here were the results for each county:
  * Denver: 82.8% and 306,055 votes.
  * Jefferson: 10.5% and 38,855 votes.
  * Arapahoe: 6.7% and 24,801 votes.
* Here were the results for each candidate:
  * Diana DeGette: 73.8% and 272,892 votes.
  * Charles Casper Stockham: 23.0% and 85,213 votes.
  * Raymon Anthony Doane: 3.1% and 11,606 votes.
* And the winner is...Diana DeGette who received 272,892 votes which is 73.8% of the total vote.

## Election Audit Summary
The analysis that was used for this election is something that can be used for any election and not limited to three specific counties in Colorado. The resources that were used for this project were:
* The data source itself (election_results.csv)
* The software to complete the script (Python 3.7.9 which was used on Visual Code 1.51.1)

Two examples for modifying the script to fit for a different election are:
* Update the script with a new output file name.
* Ensure the new .csv files contains a unique ID for each casted vote, the county, the candidate who received the votes, and only contains results for the same election.


## Extra Information
Here is a screenshot of the final analysis via Visual Code:

![Alt text](https://github.com/EJones621/Election_Analysis/blob/main/Resources/Election_Results.png)


##### The script to run the election can be found here: 
[PyPoll_Challenge.py](https://github.com/EJones621/Election_Analysis/blob/main/PyPoll_Challenge.py)

##### The elections results for the audit can be found here:
[Election_Analysis](https://github.com/EJones621/Election_Analysis/blob/main/Analysis/election_analysis.txt)
