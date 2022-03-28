# Election Results
## Using Python to Analyze Election Data 
### Purpose
To determine the voter turnout for three Colorado counties, find the percentage of votes from each county, and find the county with the highest turnout.
## Election Audit results
### County Votes:

Jefferson: 10.5% (38,855)

Denver: 82.8% (306,055)

Arapahoe: 6.7% (24,801)

Largest County Turnout: Denver

![image](https://user-images.githubusercontent.com/100768274/160320986-69aab79c-f4f9-41e1-b9fb-0ae18908cbfb.png)
### Election Audit Summary
The Code can be used in future Colorado elections. It will work for any number of counties. If the word counties is replaced in the code it will work for comparing any municipalities in an election. 

    # 7: Print the county with the largest turnout to the terminal.
    winning_county_summary = (
        f"-------------------------\n"
        f"Largest County Turnout: {winning_county}\n"
        f"-------------------------\n")

    election_results = (
        f"\nElection Results\n"
        f"-------------------------\n"
        f"Total Votes: {total_votes:,}\n"
        f"-------------------------\n\n"
        f"County Votes:\n")

The word county in the following instances of code would need to be replaced with the new municipality that is being measured.
