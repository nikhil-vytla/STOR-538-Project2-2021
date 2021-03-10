STOR 538 Project 2
==================

Project Details
---------------

### Objective
The Variables you will be predicting are Spread, Total Points, and Offensive Rebounds. <br />
Spread = Winning team's score - Losing team's score <br />
Total points = Winning team's score + Losing team's score <br />
Offensive Rebounds = Number of rebounds a team had while on offense



### Methodology
Data is available [Here](https://github.com/mattymo18/STOR-538-Project2-2021) <br />
You are asked to use this data to build models that predict the 3 variables above. These models will be used to predict NBA games from April 10th - April 30th. That schedule can be found [Here](https://www.espn.com/nba/schedule) <br />

### Grading 
You will be graded on accuracy of your models predicting these three variables. Dr. Mario will release results after each week's games ranking your projects vs your classmates. 

Data
----
Data is found in the Source-Data directory.

All Data is originally taken from [Here](https://www.kaggle.com/nathanlauga/nba-games?select=games.csv)

#### games.csv
Primary key: GAME_ID \
Foregin keys: HOME_TEAM_ID, VISITOR_TEAM_ID 

##### Variables:
  * SEASON: Season when the game occured
  * PTS_home: Number of points scored
  * FG_PCT_home: Field goal percentage
  * FT_PCT_home: Free throw percentage
  * FG3_PCT_home: Three point percentage
  * AST_home: Number of assists
  * REB_home: Number of rebounds
  
###### only home variables displayed
  
***
  
2. games_details.csv