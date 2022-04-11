# Election Analysis
An audit of results for an election in Colorado using Python.

## Overview of Election Audit
Colorado election commission wanted additional information regarding a recent election in their status. The commision wanted the following additional information:
 * The voter turnout for each county
 * The percentage of votes from each county out of the total count
 * The county with the highest turnout
 
This addiitonal request was in addition to the previously populated information of total number of votes in the election, list of candidates who received votes, and who won the election (including number of votes and percentage of votes the winner received).

## Election-Audit Results
There were 369,711 votes submitted in the election

The counties in the election:
  * Jefferson
  * Denver
  * Aranpahoe
 
The results per county:
  * Jefferson had 10.5% of votes, 38,855  votes.
  * Denver had 82.8% of votes, 306,055 votes.
  * Aranpahoe had 6.7% of votes, 24,801 votes.

The county with the largest turnout:
  * Denver

Breakdown of canidates:
  * Charles Casper Stockham who received 23.0% of votes with 85,213 votes.
  * Diana DeGette received 73.8% of votes with 272,892 votes.
  * Raymon Anthony Doane received 3.1% of votes with 11,606 votes.

The winner of the election:
  * Diana DeGette won 73.8% of votes with 272,892 votes.

## Election-Audit Summary
The script used can be repurposed to audit other elections if desired or needed by updating the file used. To help keep files from being overriden and/or confused, the file the analysis is written to should be updated and set to something for clear.

It can also be used to provide additional insight on where votes came from. If the election data were to include city of residence, whether they voted in person or by mail, or other demographical informaiton an analysis on election results could provide insight on not only who won the election but could provide a summary of who is voting.
