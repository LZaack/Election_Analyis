# County Election Analysis in Colorado

## Overview Election Audit
Tom and Seth, employees of the Colorado Board of Elections asked me to help them to complete the election audit of a recent local congressional election.
They gave me the file `election_results.csv` which contains 3 columns, and 369,712 rows of information, as can be seen in the next image:

![election_results](https://user-images.githubusercontent.com/95454286/150297997-a6767c76-c933-4486-972a-a5e56eb655fb.png)

They asked me to analyze the data and retrieve the following:

*(a)* Calculate the total number of votes cast.
*(b)* Get a complete list of candidates who receive votes.
*(c)* Calculate the total number of votes each candidate receive.
*(d)* Calculate the percentage of votes each candidate won.
*(e)* Determine the winner of the election based on the popular vote.

## Election-Audit Results
The analysis of the election data shows that:

`A. The votes cast in the election are:`

![total_votes](https://user-images.githubusercontent.com/95454286/150297953-c6fc11f2-0752-40c2-9bb6-f0df5d0b3d4e.png)

`B. The votes for each county and the percentage are:` 

![county_votes](https://user-images.githubusercontent.com/95454286/150297685-fdebe4f9-3f9b-404d-8cbc-14334e1bd7ee.png)

`C. The county with the largest number of votes is:` 

![largest_county](https://user-images.githubusercontent.com/95454286/150297700-5a2a38d2-62af-4167-9ca7-5ff184e0932f.png)

`D. The total votes for each candidate are:` 

![canidates_votes](https://user-images.githubusercontent.com/95454286/150297736-38c0ac2d-8628-43ed-9c93-0c8434acdb74.png)

`E. The winning candidate is:`

![winner_numbers](https://user-images.githubusercontent.com/95454286/150297767-636b608b-3403-4425-91b1-cfc0f45a55b5.png)

## Election-Audit Summary

The code could be refactored with the purpose of getting more information and for further elections, the commission just needs to define the data they want to achieve. For example:

*1.* With some changes to the code the commission can get the popularity of candidates in each county. It is clear that the people from Denver decide the winner, but they do not know how many people in Jefferson voted for Diana DeGette (the winner).

*2.* If the commission requests the age and the zip code of the voters, and adds it to the election results file, with a few code modifications they could identify the zones and the ages with preferences for each of the candidates. 

