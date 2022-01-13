# Election_Analysis

## Project Overview

A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of candidates who received votes.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources

* Data Source: election_results.csv
* Software: Python 3.9.7, Visual Studio Code 1.63.2

## Summary

The analysis of the election shows that:

* There were 369,711 votes cast in the election.
* The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane

* The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.

* The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Challenge Overview

The Colorado Board of Elections has requested additional data to complete the audit. The additional data includes:

  - The voter turnout for each county
  - The percentage of votes from each county out of the total count
  - The county with the highest turnout

## Challenge Summary

The additional data shows that there were three counties involved in the election. Out of the 369,711 votes casted:

- Arapahoe County had the lowest voter turnout of 24,801 voters, which is 6.7% of total voters.
- Jefferson County had the second highest voter turnout of 38,855 voters, which is 10.5% of total voters.
- Denver County had the highest voter turnout of 306,055 voters, which is 82.8% of total voters.

This script can be very useful for any future election audits. It is important that you modify this script so that it works with the election information of your choice.

1. The file path for the CSV file is specific to this election. It is important that you change the file path to match the location of your election results. This change can be done on line 9 of the `PyPoll_Challenge.csv` file. It is also important to note that an additional directory named "analysis" needs to be added to your computer and the file path for this directory needs to be changed as well. This change can be done on line 11 of the same file.

![file_path_change](images/path_change)

2. Inspect your CSV file with the election results and look at the order of the header. In this code, we specify that the county is in column 2 and the candidate's name is in column 3. If your CSV is ordered differently, the changes can be made on line 47 and line 50 of the script. **Remember that the number inside the square bracket is the _index_, which is _one less_ than the number of the column.**

![column_index_change](images/column_change)