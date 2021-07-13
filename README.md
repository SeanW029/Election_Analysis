# Election_Analysis

## Overview of Election Audit: 

The purpose of this election audit analysis is to present futher data on the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout to the election commission to complete their audit. 

## Election-Audit Results:

* A total of 369,711 votes were casted in this congressional election.
* Breakdown of the number of votes and the percentage of total votes for each county in the precint:

  Jefferson: 10.5% (38,855)
  Denver: 82.8% (306,055)
  Arapahoe: 6.7% (24,801)
  
* Denver county had the largest number of votes.
* Breakdown of the number of votes and the percentage of the total votes each candidate received:

  Charles Casper Stockham: 23.0% (85,213)
  Diana DeGette: 73.8% (272,892)
  Raymon Anthony Doane: 3.1% (11,606)  
  
* Diana DeGette won the election with a vote count of 272,892 votes, and the percentage of the total votes is 73.8%.

## Election-Audit summary:

Based on the raw data provided by the election_analysis.csv, I used Python scripts to extract the data related to this election, namely the participating counties, number of votes received by each candidate from their respective counties, and the percentage of their votes in total votes received. The specific process used is the FOR loop that counted votes from different counties and their vote casts, with the help from creation of dictionaries, empty strings and variables to define the scope of this loop. One example is the creation of county_dict dictionary that enabled addition and retrieval of vote counts. Another important process used is the IF stament that determines the winning county and the vote counts, and the example here is the Denver that has been determined as the county with the largest number of votes as a result of the IF statement. 

This analysis tool can be applied to analyze election results in other precints, with modifitions to the raw data csv file in the format of ballot ID, county and candidate. With the dictionaries and varaibles created, this analysis tool can provide same types of election results as above. 

It could also provide different results such as the county that receives smallest number of votes if we modify the IF statement for statistical review. 
