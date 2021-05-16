# PyPoll Analysis

## Election Audit Overview
This Python script was created to assist Tom, a Colorado Board of Elections employee, in an election audit of the tabulated results for US Congressional precinct in Colorado. The scope of work is to report the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, the winner of the election based on the popular vote, the county with the largest turnout, and votes cast per county.

## Election Audit Results: 
The results for the election audit are as follow:

**County Results:**
 * Jefferson: 10.5% (38,855)
 * Denver: 82.8% (306,055)
 * Arapahoe: 6.7% (24,801)
 * Largest County Turnout: Denver

**Candidate Results:**
 * Charles Casper Stockham: 23.0% (85,213)
 * Diana DeGette: 73.8% (272,892)
 * Raymon Anthony Doane: 3.1% (11,606)

**Election Results:**
 * Total Votes: 369,711
 * Winner: Diana DeGette
 * Winning Vote Count: 272,892
 * Winning Percentage: 73.8%


## Election Audit Summary

This script can be used for any election as the election_results.csv file can be updated with new election data and the results will be saved to the election_analysis.txt file. To use the scrip for a new election, follow these steps:

 1. Update the election_results.csv file with the new election data.
 2. Save the file to the Resources folder as this is where the script will take the information from as shown below in the file_to_load object.
 
   ![Screen Shot 2021-05-16 at 9 56 39 AM](https://user-images.githubusercontent.com/17945476/118400956-c3d37500-b631-11eb-858f-e4d492b43340.png)
   
 3. Run the script.
 4. Open the election_analysis.txt file to see the results as this is where the script will print the results as shown below in the file_to_save object.
 
   ![Screen Shot 2021-05-16 at 9 56 39 AM](https://user-images.githubusercontent.com/17945476/118400956-c3d37500-b631-11eb-858f-e4d492b43340.png)
   
The direct file path can be updated to show an indirect file path if the file is saved to a different folder as shown in the picture below.

  ![Screen Shot 2021-05-16 at 10 20 54 AM](https://user-images.githubusercontent.com/17945476/118400974-db126280-b631-11eb-8487-c81cd22b1e42.png)
