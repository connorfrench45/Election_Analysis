# Election_Analysis

## Project Overview
A Colorado Board of Elections employee had given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who receiverd votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.7, Visual Studio Code current version (as of 4/7/2022)

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The results were for each candidate:
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
- The winner of the election was
  - Diana DeGette, who received 73.8% of the vote and 272,892 votes.

## Challenge Overview
In addition to the work done previously, it was requested to find the tally of votes based on county, and have the results printed out neatly on election_analysis.txt

## Challenge Analysis and Summary
#### Analysis
The further analysis shows that:
- The county vote totals were:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
- The largest county by vote total was:
  - Denver with 306,055 votes amounting to 82.8% of all votes cast

#### Summary
The script is extremely versatile. As written it can be used for any election as long as the data is in the same format as it was presented here and in the same file structure (nested in a Resources folder). If the csv file was in a different path, then this code:
```
# Add a variable to load a file from a path.
file_to_load = os.path.join("Resources", "election_results.csv")
```
Would have to reflect the different file path. If the csv was organized differently, then the code referencing the specific objects would have to be corrected.
