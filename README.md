# mining_warcraft

Team Members: Ellen Hendricks, Jennifer Collins, Sarah Small

Project Title: Mining Warcraft

Description:  Finding trends in Warcraft for popularity over time, by demographics, and YouTube presence, and examine the in-game economy

Data: Blizzard API (https://dev.battle.net)for statistics: profile and game data available; RealmPop for geographic/regional breakdowns
(appears to be data from battle.net, too). 


3-5 initial research questions:
1.	First, what are the basic user stats…can we track all user data by gender and age over time?
2.	Can we track how long the average user ‘sticks around’? Frequency and duration of ‘breaks’ from playing
3.	What kind of player to player buy/sell/trade actions happen? Examine trends within the ‘in-game economy’
4.	Is it possible to track popularity with YouTube video views? Start with number of channels, expand into number of video views?

Techniques and Tools: slack channel and git repository established

Data Shortcomings: not available yet

=============Update 8/7/2018==============

Comments on Data Sources and Shortcomings:

Having difficulties finding demographic stats over time from Blizzard API, and do not appear to get actual player data, but can get character, faction, and guild statistics by region/server. Use stock market history and create dataframe to analyze numbers by expansion release dates.

Revised / 3 strong research questions: 

1. Does a player's region affect their character faction selection? (i.e. Is the distribution of factions 50/50 by regions?) Null Hypothesis: Region does not affect choice in character faction.

2. Is there a faction that is more dedicated to playing? Measure this through level of progression through the game and/or PVP rank. Null Hypothesis: Players are likely to progress through the game regardless of faction or PVP rank.

3. Is there a correlation between stock values of Blizzard and Expansion version releases for WOW? 
   Null Hypothesis: There is no correlation between Blizzard Stock value and expansion version release dates.

=============================Update 8/11/18==============================================================

Decided to change project direction to bikesharing after being unable to get available data to work for WOW project

Project Title: Bike Sharing Trends in Los Angeles
Data Sources: https://catalog.data.gov/dataset/metro-bike-share-trip-data
              https://miningwarcraft.slack.com/files/UC2NAQDEF/FC65TN2CA/la_weather_2016_2018.csv
1. Track daily total usage over time in LA to get started.
2. When is the most popular time of day for shared bike usage? Most popular day of the week?
3. Does temperature, precipitaiton, or air quality have an impact on number of daily rides?
4. Does the type of fare paid affect when bikes are being used?
Bonus
5. Run general comparisons for LA vs NY or DC data dependent overall usage

Data issues: having trouble accessing air pollution data, but did get more comprehensive data from metro api to cover more years.

=============================Update 8/21/18==============================================================

List of Notebooks:
Project_One_DataCleaningAndFormatting - The code used to reformat the start time and split out the quarters from the original data
Project_One_RidesPerDayAndMonth - All plots by day or by month
Project_One_DaysOfWeek - All plots by days of the week
Project_One_TimeOfDay - All plots from binning the time of day
Project_One_comparetoNY - This needed its own date fixing, another different format.  Just the one plot.



  
