### _NBA_analysis : Machine Learning Branch_

## UPDATE - Segment 2

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
* Our elbow curve indicated that would be used to 2, however we are experimenting with other numbers as well.