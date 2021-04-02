# Election_Analysis<br><br>

In this module challenge, I have been asked to help with the election analysis for the State of Colorado and their respected Election Commission.  I will be using Python Code through Visual Code Studio to assist the analysis, confirmation, and audit of election results since we have ~370K lines of raw data.  In this election analysis, I will be performing calculations on as well as calling data from our election results csv file. The data consists of a number for the ballot ID, a name for the county, and the candidate who received the vote.  <br><br>


**Overview of Election Audit**<br><br>
For this audit to be well received, trust and respected, we will need to we need to read, process, and analyze, data in the file.  The foundation of our analysis is built around a breakdown of the number of votes and the percentage of the total votes each candidate received as well as which candidate won the election, what was their vote count, and what was their percentage of the total votes.  The election commission has requested some additional data to complete the audit:<br><br>
•	The voter turnout for each county<br>
•	The percentage of votes from each county out of the total count<br>
•	The county with the highest turnout<br>

**Election Audit Results**<br><br>
Below is an image that captures the entirety of the analysis and audit that we completed for the State of Colorado Election Commission.  This information is found in the terminal when we run the script.  As we work our way down the bullet points, the image was created from the text file that was created and stored within the analysis folder titled Election Results.<br>

 ![D1_Election_Results](analysis/D1_Election_Results.png)<br><br>

   o	How many votes were cast in this congressional election?<br><br>
 For this congressional election, there were a total of 369,711 total votes cast.  As we continue down the bullet point ladder, we will be able to dissect and learn from the total number of votes that have been collected.<br>
 ![Total_Votes_Election_Results](analysis/Total_Votes_Election_Results.png)

        
   o	Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.<br><br>
The breakdown for the total county votes is as follows for the three reporting counties.  Jefferson County was the first county to report, and they contributed 10.5% of the vote for a total of 38,855 votes.  The next county that we were able to analyze and breakdown the percent contributed to the overall vote is Denver County with 82.8% of the total vote that equated to 306,055 votes.  The lowest contributing county was Arapahoe County and their proportion of the vote cast was equal to 6.7% being derived from 24,801 total votes counted.<br><br>
 ![Breakdown_Votes_Election_Results](analysis/Breakdown_Votes_Election_Results.png)
        
   o	Which county had the largest number of votes?<br><br>
 The county that had the largest voter turnout was Denver County.  Much like the overall winning candidate, Denver County won the County Voter Turnout in a landslide, Denver County was responsible for 82.8% of the election. <br>
![Largest_County_Election_Results](analysis/Largest_County_Election_Results.png)<br><br>
        
   o	Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.<br><br>
You will see that between the three candidates, the votes were distributed as follows:<br><br>
Charles Casper Stockham received 23.0% of vote and a total of 85,213 votes.  Diana DeGette received a total of 73.8% of the vote which translated to a total of 272,892 votes cast in her favor.  More on her in the bullet point below.  Raymon Anthony Doane was the lowest vote getter of the evening with the candidate receiving 3.1% of the total vote for a total number of 11,606 votes.<br><br>

![Candidates_Votes_Election_Results](analysis/Candidates_Votes_Election_Results.png)
       
   o	Which candidate won the election, what was their vote count, and what was their percentage of the total votes?<br><br>

Our results tell us that Diane DeGette is the winner of the election with 73.8% of the vote and 272,892 votes.<br><br>
![Winner_Votes_Election_Results](analysis/Winner_Votes_Election_Results.png)



**Election Audit Summary**

After deep analysis, I would like the Election Commission to know that with a few modifications to the code this script can be used in many future elections.  In my opinion, I think we need to incorporate two data points that would make this election analysis and audit complete.  The first piece of data I would like to collect and modify the script to incorporate and report, is the date and time that the voter cast their vote.  Was the majority of the votes taken during early voting or on election day?  Also, was the vote given in person or was it a mail-in ballot?  This type of analysis will help the Election Commmission know where to place their volunteers and create efficiencies in creating the final result for the total vote.  Second, we need to capture and report the total voter turnout vs the potential turnout calculated from the total number of voters registered.   We know that Denver County cast 306,055 votes but how many voters did not cast a vote?  Couple that with registered political party and we are drilling down to the nuts and bolts of the complete voter makeup in any given City, County or State.
