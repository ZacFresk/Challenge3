# Election Audit
 
## Overview

This challenges purpose was to use Python in order to create a script that would provide the total votes and percentages for your list of countries

Once the election winner had been established and the analysis of the largest country was done the results in the audit were as followed:

1.) Total Election Votes

2.) Vote turnout by country and largest voter turnout

3.) Votes by candidate in total votes and percentage

4.) Winner of election in total votes and percentage

![election_results](https://user-images.githubusercontent.com/107363203/179429658-c07d5a2b-991f-4c19-82f0-c1df202d743f.png)

## Analysis

1.) How many votes were cast in this congressional election?

* 369,711 votes were cast in Arapahoe, Denver, and Jefferson.
      
We were given the data for this, for the next step we needed to create a code to count each row and provide the count of votes.

This is the example of code we used:

![vote_code1](https://user-images.githubusercontent.com/107363203/179430215-0c9d5f51-d7f0-4f88-8e14-e11cc0feedcf.png)

Once the total votes is set to 0 this will count each row to get the total votes.

![vote_code2](https://user-images.githubusercontent.com/107363203/179430218-e3ab3a22-6d96-4f07-abf9-2987978a9662.png)

2.) Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

 * Arapahoe County: Total - 24,801 Percentage total votes- 6.7%
 * Denver County: Total - 272,892 Percentage total votes- 73.8%
 * Jefferson County: Total - 38,855 Percentage total votes- 10.5%

Using an "if-statement" will help us get the total votes and percentages we are looking for.

![vote_percentages1](https://user-images.githubusercontent.com/107363203/179430366-e5c91c2a-97fc-4092-8241-04710bfcc3d8.png)

Then we have to establish a list with unique county names so that we do not duplicate data will be present.

![vote_percentages2](https://user-images.githubusercontent.com/107363203/179430382-7ecc1860-1acc-4ec4-b869-73661f68bd26.png)

Once we have the total votes we can break the total amount for each county.

![vote_percentages3](https://user-images.githubusercontent.com/107363203/179430387-201abf73-3c34-44c7-9c99-6ffc115e24b1.png)

3.) Which county had the largest number of votes?

 * Denver County was the county with the largest voter turnout

Using this code we can get the county with the largest vote turnout. The code here is just comparing all the total votes for each county and providing us the one with the largest turnout.

![vote_turnout](https://user-images.githubusercontent.com/107363203/179430512-df1d86f5-9651-4737-bc03-12faa6cdec07.png)

4.) Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

 * Charles Casper Stockham had $85,213 total votes with 23% of the total votes.
 * Diana DeGette had $272,892 total votes with 74% of the total votes.
 * Raymon Anthony Doane had $11,606 total cotes with 3% of the total votes.
     
We changed the variables in the code candidate options and names in order to get the counts and percentages.     

5.) Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

 * Diana Degette won the election, she had a total of 272,892 votes, she had the majority of the total votes with 74% ballots.

This code was the same as the one used to get the largest county turnout but we changed the candidate variables to get the person with largest vote count.

## Summary

We used a script which would focus on three countries, Arapahoe, Denver, and Jefferson. We are certainly able to expand on this by changing the counties or even adding states. I had fun working through this challenge as we took an idea and expanded on it a few times in order to get a solid set of results. I can only imagine how far this type of script can go. I look forward to expanding on this in the future.

### Example: 

We could implement to the script the amount of votes each candidate had for each county. This could be useful information to people running the election to determine if there are any differences between candidates for each county.

### Example:

We could also implement to the script the amount of people in each county that were either registered to vote and did not vote or the amount of people who were registered and did not vote. This would be great information to provide as it could allow for better campaign strategies for the people running.
