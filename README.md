# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you that following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Detemine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election show that:
- There were "369,711" votes cast in the election.
- The candidates were:
  - Candidate 1: Charles Casper Stockham
  - Candidate 2: Diana DeGette
  - Candidate 3: Raymon Anthony Doane
- The Candidate  results were:
  - Candidate 1: Charles Casper Stockham received 23.0% of the vote and 85,213 number of the votes.
  - Candidate 2: Diana DeGette received 73.8% of the vote and 272,892 number of the votes.
  - Candidate 3: Raymon Anthony Doane received 3.1% of the vote and 11,606 number of the votes.
- The winner of the election was:
  - Candidate 2: Diana DeGette who received 73.8% of the vote and 272,892 number of the votes.

--------------------------------------------------------

## Challenge Overview

### Purpose
   The purpose of this analysis is to help Seth and Tom complete some additional data, the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout, before submiting the election audit results to the election commission.
	
## Results: 

**1. How many votes were cast in this congressional election?**
	
   > There were 369,711 total votes in this congressional election.

![1 Total_votes](https://user-images.githubusercontent.com/89308251/132901288-b0ce60ce-50d5-4f6e-99d1-f69152411ac2.png)


**2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.**
	
   - County Votes:
      - Jefferson: 10.5% (38,855)
      - Denver: 82.8% (306,055)
      - Arapahoe: 6.7% (24,801)

![2 County_votes](https://user-images.githubusercontent.com/89308251/132901378-e16d43b1-8d2b-4c0c-8783-2054613a777c.png)


**3. Which county had the largest number of votes?**
	
   > The largest number of votes is Denver county.

![3 Largest_county](https://user-images.githubusercontent.com/89308251/132901495-bc829376-ba47-4cc2-8cf3-241b4e62d53e.png)


**4. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.**
	
   - The total votes of each candidate:
      - Charles Casper Stockham: 23.0% (85,213)
      - Diana DeGette: 73.8% (272,892)
      - Raymon Anthony Doane: 3.1% (11,606)

![4 Total_votes_each_candidate](https://user-images.githubusercontent.com/89308251/132901515-0d8b1dcf-5017-4ac8-b430-292b4f08f0c8.png)


**5. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?**
	
   > The winner is Diana DeGette. She got 272,892 out of 369,711 votes or 73.8% of the total votes.
 
 ![5 The_winner](https://user-images.githubusercontent.com/89308251/132901535-ed9457f7-55fb-40f5-ab97-b4016ff2fc33.png)


## Challenge Summary

- This script can be used for any kind of election. We may need to make some small changes to allow the code to work with different data, but that should not be a problem. 
  
   > The first example of a different kind of election would be a very simple school election for choosing the student body president. This script can be modified by changing the county votes to student grade levels instead.   
   
   > The second example would be a nationwide presidential election. We could either change county to be state instead or we could add state in addition to county so we would have more detail. 
    	

