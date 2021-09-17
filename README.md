STOR 538 Project 2
==================

Project Details
---------------

### Objective
The Variables you will be predicting are Spread, Total Points, and Offensive Rebounds. <br />
Spread = Winning team's score - Losing team's score <br />
Total Points = Winning team's score + Losing team's score <br />
Offensive Rebounds = Number of rebounds a team had while on offense

### Methodology
Data is available [Here](https://github.com/mattymo18/STOR-538-Project2-2021) <br />
You are asked to use this data to build models that predict the 3 variables above. These models will be used to predict NBA games from April 10th - April 30th. That schedule can be found [Here](https://www.espn.com/nba/schedule) <br />

### Grading 
You will be graded on accuracy of your models predicting these three variables. Dr. Mario will release results after each week's games ranking your projects vs. your classmates. 

***

Data
----
Data is found in the Source-Data directory.

All Data is originally taken from [Here](https://www.kaggle.com/nathanlauga/nba-games?select=games.csv)

### games.csv
Primary key: GAME_ID \
Foreign keys: HOME_TEAM_ID, VISITOR_TEAM_ID 

#### Variables:
  * SEASON: Season when the game occured
  * PTS_home: Number of points scored
  * FG_PCT_home: Field goal percentage
  * FT_PCT_home: Free throw percentage
  * FG3_PCT_home: Three point percentage
  * AST_home: Number of assists
  * REB_home: Number of rebounds
  
#### Description
This data set contains game by game boxscores for home and away teams. Variables are aggregates over the whole game. 

###### only home variables displayed
  
***
  
### games_details.csv
Primary key: PLAYER_ID \
Foreign keys: GAME_ID, TEAM_ID 

#### Variables:
  * TEAM_ABBREVIATION: Team name abbreviation
  * TEAM_CITY: Team city
  * PLAYER_NAME: Player name
  * START_POSITION: Starting position of the player, `NULL` if player came off the bench
  * COMMENT: A comment about the player, usually health related
  * MIN: Minutes played
  * FGM: Field goals made
  * FGA: Field goals attempted
  * FG_PCT: Field goal percentage
  * FG3M: Three pointers made
  * FG3A: Three pointers attempted
  * FG3_PCT: Three point percentage
  * FTM: Free throws made
  * FTA: Free throws attempted
  * FT_PCT: Free throw percentage
  * OREB: Offensive rebounds
  * DREB: Defensive rebounds
  * REB: Rebounds
  * AST: Assists
  * STL: Steals
  * BLK: Blocks
  * TO: Turnovers
  * PF: Personal fouls
  * PTS: Points scored
  * PLUS_Minus: Plus-Minus
  
#### Description
This dataset contains player level date for each game. Variables are aggregates over the whole game.

***

### teams.csv
Primary key: TEAM_ID

#### Variables:
  * ABBREVIATION: Abbreviation of team name
  * NICKNAME: Team nickname
  * YEARFOUNDED: Year the team was founded
  * CITY: Home city
  * ARENA: Home arena
  * ARENACAPACITY: Arena capacity, `NULL` if unknown
  * OWNER: Team owner
  * GENERALMANAGER: Team GM
  * HEADCOACH: Team coach
  * DLEAGUEAFFILIATION: D-league team affiliate
  
#### Description
This dataset contains general team data. 
