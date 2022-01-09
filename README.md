# eEection_Analysis

## Overview
The purpose of this analysis is to make a software to help Seth and Tom with an election audit to see who has won the election between 3 candidates and also which counties had the highest turnout, including their percentages. 

### Analysis
The county with the Highest vote turnout was Denver, with 82.8% of votes casted, 306,055 votes. Jefferson had 10.5% with 38,855, Arapahoe had 6.7% with 24,801. For the Candidates, Charles Casper Stockham had 23.0% with 85,213 votes casted, Diana DeGette had 73.8% with 272,892 votes casted, Raymon Anthony Doane had 3.1% with 11,606 votes casted. The winner as a result was Diana DeGette. 

![Screenshot!](https://github.com/adarisi7/eEection_Analysis/blob/e6a9e3bb86c347ab75cca94bf868f7bc932f1f1e/Election_Analysis/Screen%20Shot%202022-01-09%20at%202.33.35%20AM.png)

![Screenshot1!](https://github.com/adarisi7/eEection_Analysis/blob/3f874d80b8582df461bd202fcbc3bb8774bdd1c0/Election_Analysis/Screen%20Shot%202022-01-09%20at%202.46.09%20AM.png)

### Script Modification
This program would be very useful for measuring the popular vote for any candidates as well as their counties for local elections. One way we could modify it is my making it on a national level. We would first have to take in all the counties in the entire country in a csv file. Then, instead of a popular vote we have to do an electoral college. To do this, we could read 50 csv files which represent each state, and we could write python program to determine whether each state is red or blue depending on the counties weighted with population. Then we can merge them in one big loop to keep track of red and blue, and break the loop once a red or blue hits 270 and declare the winner of the election.
