# Election_Analysis

## Analysis Overview
The 'Election Analysis' report was request by a Colorado Election Commmission Board for a breakdown of the voter turnout for each county, percentage of votes from each county out of the total count, and the county with the highest turnout.  For this analysis, the below were the specified requirements asked.

1. Calculate the total number of votes cast.
2. Calculate the total number of votes from each county.
3. Calculate the percentage of votes from each county.
4. Get a complete list of candidates who received votes.
5. Calculate the total number of votes each candidate received.
6. Calculate the percentage of votes each candidate won.
7. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election Audit Results
The analysis of the election show that (shown in **Figure 1**):
- There were "369,711" votes cast in the election.'
- The counties that casted votes:
  - Jefferson votes comprised of "10.5%" of the votes and "38,855" number of votes.
  - Denver votes comprised of "82.8%" of the votes and "306,055" number of votes.
  - Arapahoe votes comprised of "6.7%" of the votes and "24,801" number of votes.
- The largest county turnout:
  - Denver
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Taymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received "23.0%" of the votes and "85,213" number of votes.
  - Diana DeGette received "73.8%" of the votes and "272,892" number of votes.
  - Taymon Anthony Doane received "3.1%" of the votes and "11,606" number of votes.
- The winner of the election was:
  - Candidate Diana Degette, who received "73.8%" of the vote and "85,213" number of votes.

**Figure 1** - Election Results
INSERT IMAGE

## Python Code
In this section we will go over the Python code that was used to extract the data from the given 'CSV' from the Election Commission Board and calculate the given totals and percentages that we have seen above.

#### Total Votes
**Figure 2** - Total Votes
INSERT IMAGE

To calculate the total votes that were cast in this congressional election seen in **Figure 2**, the given *election_results.csv* needed to be loaded first so Python had a reference point to pull the necessary data seen in **Figure 3**.

**Figure 3** - Election Results CSV Example
INSERT IMAGE

Next, a variable was created on *line 14* to initialize the vote counter and it was set to zero.  On *lines 37-47* Python is instructed to open the *election_results.csv* and read the data as a variable called *election_data* and to read the header information in each column but to skip it as data used for votes. Reference **Figure 4**.

**Figure 4** - Python Total Votes
INSERT IMAGE

In order for the total votes to be printed out and saved, Python was instructed to open a text file called *election_analysis.txt* on *line 83*, a variable called *election_results* on *line 86* was created to house the total votes and print to the text file, and on *line 94* to save the total votes and the printed information to the *election_results.txt*. Reference **Figure 5**.

**Figure 5** - Python Total Votes Print Ouput and Save
INSERT IMAGE

#### County Votes and Percentages of Votes
**Figure 6** - County Votes and Percentages of Votes
INSERT IMAGE

#### Largest County Turnout
**Figure X** - Largest County Turnout
INSERT IMAGE

#### Candidate Votes and Percentages of Votes
**Figure X** - Candidate Votes and Percentages of Votes
INSERT IMAGE

#### Winning Candidate
** Figure X** - Winning Candidate
INSERT IMAGE

## Election Audit Summary
