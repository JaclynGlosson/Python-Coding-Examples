# Python Coding Examples
If you're looking for other examples of my coding skills in python, this repository dedicated to showcasing coding assignments completed during my coursework.

## SEPTA Schedule Creation
This notebook pulled real-time data for incoming SEPTA Suburban Station trains, and organized it in a readable schedule format. The main challenge associated with this exercise was that the accessed data did not include AM/PM designation for time, and therefore I had to manually assign AM/PM to each observation based on the time the data was requested. Finally, I output the data into hourly logs.

## Word use in Loan Applications
Using the Lending Club Loan Dataset, I begin by parsing words used in both "good" and "bad" loan applications. I then create a dictionary of the top 25 most frequently used words, which end up being very similar between both type of loans. I then identify the most frequent words uniquely used in each type of loan.
* Good loans: rate, !, it, lower
* Bad loans: bills, consolidation, need, help

## Sportrader Standing Table
Using the Sportradar Soccer v4 API to obtain data from the 2020-2021 season for the English Premier League, I create a standings table to organize match metrics for each team. The final standings table showcases:
* abbreviation of team name
* games played
* games won
* games drawn (ties)
* games lost
* goals for (total made)
* goals against (total conceded)
* goal difference
* total points
