![nba_league]([[images/nba.jpeg](https://github.com/abeituni/NBA_analysis/blob/main/Dashboard/Images/nba.jpeg)])
# **NBA Analysis - Segment 3**
A shared repository for the final project: NBA Performance Analysis.

## Presentation 
Our presenation is hosted on [Google Slides](https://docs.google.com/presentation/d/1L4YRwSEaInupFLXlQvdWhKHDKyJHGeozT8aQ3ug04TQ/edit?usp=sharing).
##### *Topic*
A combination of NBA season averages and advanced stats from 5 seasons were clustered using unsupervised machine learning. We want to visualize how NBA players can be grouped according to their stats and performance.

##### *Reason for selecting topic*
With the high interest we have in basketball and all the available data we have for this industry, we want to use our data analytic skills to dig deep into analyzing NBA players.

##### *Description of source of data*
- The data is gathered from [Basketball Reference](http://basketball-reference.com/)
- We used the NBA player stats and advanced stats; specifically season averages per game. 


##### *Question that we hope to answer*
We hope to find out which NBA players have the most similar stats spanning across seasons from 2016 through 2021.


## Github

##### *Branches were created for each team*

## Dashboard
We have included a link to our visualization & analysis for our Advanced Stats Model below. 
[Advanced Statistics - Tableau Visualization (https://public.tableau.com/app/profile/jacob.steinfeld/viz/NBA_16436804554500/advanced_stats?publish=yes)

## Machine Learning

## UPDATE - Segment 3

1) Description of preliminary data preprocessing
   -Same as segment 2
2) Description of feature engineering & feature selection
   -Decided to use PCA for each learning model we are working on
3) Description of how data was split
   -We split the data into 4 models we'd work on; Traditional, Advanced, Shooting & Defensive Stats
4) Explanation of model choice
   -We had tons of data to work with from our original data sets, so we decided to split them up into 4 unsupervised machine learning models to drill down on the data we were working with. 
5) Explanation of changes in model choice
   - Last week we did not have the 4 models finalized. We have done so this week and they are all complete minus the Defensive Stats model.
6) Description of how model training has been going
   - Model training has been a little challenging, but very interesting. We have been splitting our classes from model outputs into smaller classes, therefore drilling down on the data.

## Update - Segment 2
1) Description of preliminary data preprocessing

- split original dataframe into two dataframes, main and miscellaneous.
- converted uppercase column names into lowercase for postgres.
- used groupby() by player name.


2)  Description of preliminary feature engineering and preliminary feature selection, including their decision-making process

:  Decided to use PCA due to the high number of input features. Used PCA to reduce number of features. Got smaller sets of dimensions, 5 principal components.

3)  Description of how data was split into training and testing sets

: We are using Unsupervised Machine Learning. Traning and splitting process was not needed.


4)  Explanation of model choice, including limitations and benefits

* started machine learning process by using the elbow curve. Looped through 10 values for K and determined inertia. Created plot for the elbow curve and created k-means function.
* Used PCA to reduce number of features. Got smaller sets of dimensions, 5 principal components.
* Used elbow curve with the newly generated principal components. K value is 3.
* Plotted the clusters. 


## Update - Segment 1

* Our first ML model took in all of our statistical stats into the machine. The elbow curve indicated we should use 2 clusters. 
* We decided to ignore the elbow curve for the model and use 5 clusters instead. Our idea behind this was we wanted our first model to group the players by 5 

### Tools
* We will use an Unsupervised Machine learning to cluster players based off of its judgements on the statistics presented to them. 


## Database
See [Database branch](https://github.com/irameowlee/NBA_analysis/tree/database_branch)
    
See [Technology branch](https://github.com/irameowlee/NBA_analysis/blob/technology_branch/README_technology.md)

## Dashboard
We are using Tableau to created our visualizations and storyboard. 


