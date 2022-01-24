# NBA_analysis
The technologies & programs we will be implementing for our project are listed below.

#### Data Source: 
We utilized NBA player statistics from basketball-reference.com. The website allowed us to download the data into CSV files. We downloaded ten CSV files, one for each season with the individual player statistic and one with advanced statistics for each season. We collected fives season from 2016 to 2021.

#### Cleaning/Formatting Data:
We created a jupyter notebook file, "CleaningData," to read into CSVs files and re-format columns using Python. We used Pandas to create DataFrames from the CSVs and merge them into one DataFrame per season. We then exported new cleaned CSV files.

#### Database Storage: 
We created another jupyter notebook to take the clean CSV files and import them into a Postgres database using SQL Alchemy and Python. We also created a schema file to create two tables for our Analysis using SQL.
#### Machine Learning: 
We created a python jupyter notebook file to conduct our machine learning models. We used SkLearn library to perform our PCA analysis. We've also decided to use an unsupervised learning model to predict player performance, and we used the SkLearn library for this as well.
##### Visualization: 
We've decided to use Tableau to display our results and machine learning models. However, we are currently using Microsoft Visio to create our Storyboard. We hope to convert this to Tableau.
### Storyboard on Google Slides:
We are currently using Microsoft Visio to create a wireframe for our storyboard. We hope to display this in our Google Slides. We hope to convert the visualizations to Tableau and link the webpage to our presentation. We are thinking to switch to the Tableau webpage during the presentation so we can display the interactive elements of our visualizations.
