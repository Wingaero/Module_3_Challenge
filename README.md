# Module_3_Challenge

## Overview of Election Audit: 

#### The purpose of this election audit analysis is to provide a summary of the provided data about the election with the inclusion of additional data.  
#### This additional data is as follows:
    - The voter Turnout for each county
    - The percentage of the total votes from each county out of the total count
    - The county with the highest turnout



## Election-Audit Results: 
Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.


- How many votes were cast in this congressional election?
        - 1. Initialized Variable for Total Votes in Election
![Initialized Variable for Total Votes in Election](Resources/election_challenge_ttlvotes_init.png)

        - 2. Looped value for Total Votes in Election
![Looped value for Total Votes in Election](Resources/election_challenge_reader_loop.png)

        - 3. Print number of Total Votes in Election to a text file
![Print number of Total Votes in Election to a text file](Resources/election_challenge_ttlvotes_write_to_file.png)

        - 4. Number of Total Votes in Election in text file
![Number of Total Votes in Election](Resources/election_challenge_ttlvotes_write.png)

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

        - 1. Initialized Variables for holding data
![Text data for every countys total votes and percentage of total](Resources/election_challenge_county_votes_init.png)

        - 2. For loop creating county list
![for loop creating county list](Resources/election_challenge_reader_loop.png)

        - 3. Text data for every countys total votes and percentage of total
![Text data for every countys total votes and percentage of total](Resources/election_challenge_county_votes_write.png)

- Which county had the largest number of votes?

        - 1. Initialized variables for largest county data
![Initialized variables for largest county data](Resources/election_challenge_largest_init.png)

        - 2. Calculation of largest county data
![Largest county data calculation](Resources/election_challenge_largest_calc.png)

        - 3. Text data for largest county data
![Text data for candidates](Resources/election_challenge_largest_write.png)


- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

        - 1. Initialized variables for candidate votes data
![Initialized variables for candidate data](Resources/election_challenge_cand_votes_init.png)

        - 2. For loop creating candidate list
![for loop creating candidate list](Resources/election_challenge_reader_loop.png)

        - 3. Calculation of candidate vote data
![Candidate vote data calculation](Resources/election_challenge_cand_votes_calc.png)

        - 4. Text data for every candidates total votes and percentage of total
![Text data for candidates](Resources/election_challenge_cand_votes_write.png)

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

        - 1. Initialized variables for candidate votes data
![Initialized variables for winning candidate](Resources/election_challenge_win_init.png)

        - 2. Calculation of winning candidate data
![Candidate vote data calculation](Resources/election_challenge_win_calc.png)

        - 3. Text data for the winning candidate
![Text data for winning candidate](Resources/election_challenge_win_write.png)



## Election-Audit Summary: 

#### This script is very easily customizable for any election with certain modifications.  The first thing that needs to be changed is the path to the data.
![Business Proposal 1](Resources/election_challenge_bus_prop1.png)
#### If some more variables are created for state data and the calculation of county data is changed for state data, this can easily be used for a national election.
#### This election will only need its own .csv file storing all of the vote data in the format provided for this script with the inclusion of state data.
