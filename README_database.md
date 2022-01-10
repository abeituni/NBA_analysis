# NBA_analysis
## Database: Segement 1

### Rubric: 
Team members present a provisional
database that stands in for the final
database and accomplishes the
following:
✓ Sample data that mimics the
expected final database structure or
schema
✓ Draft machine learning module is
connected to the provisional database

### Summary of Process:
This week our team has created [name of database]
using data from https://www.basketball-reference.com/leagues/NBA_2021_advanced.html. After we cleaned the data, we uploaded our cleaned csv files to a Postgres database. We've utilized our ERD (see image file) to created our database structure. We also created a schema file: schema.sql to create the tables to be read into Postgres. See image below of database creation.

#### NBA Analysis Database
![](https://i.imgur.com/sZpdt5f.png)

### Database Column Acronyms:
* Index = Unique Player rank
* MP = Minutes Played
* G = Total Games
* GS = Games Started
* P = Minutes Played
* FG = Field Goal
* FGA = Field Goals attempted
* FG% = Field Goal percentage
* 3P = 3-points made
* 3PA = 3-points attempted
* 3P% = 3-point percentage
* 2P = 2-points made
* 2PA = 2-points attempted
* 2P% = 2-point percentage
* eFG% = effective field goal percentage
* FT = Free throws made
* FTA = Free throws attempted
* FT% = Field Throw percentage
* ORB = Offensive Rebounds
* DRB = Defensive Rebounds
* TRB = Total Rebounds
* AST = Assists
* STL = Steals
* BLK = Blocks
* TOV = Turnovers
* PF = Personal Fouls
* PTS = Total Points
* PER = Player Efficiency Rating
* BPM = Box Plus/Minus
* VORP = Value over replacement player
