# Exploratory Data Analysis for Microsoft Studio

##### Author : Nurulain Abdi

## Overview

#### Project: 

Microsoft is a tech company that wants to venture into video content creation and they have decided to create a new movie studio.

#### Goal: 
Exploring the types of films that are topping box office movies in terms of income, genre and the length of films to be produced using different data analysis methods to help Microsoft’s team decide what type of films to create.

#### Data I worked with:

•	imdb title.basics
•	imdb.title.ratings
•	bom.movie_gross


## Methods

#### Data cleaning :

I first imported all the necessary libraries that I will use for explotary data analysis, I then cleaned the data by getting rid of missing values by either dropping them entirely or adding zero in order to maintain data continuity
There were a lot of duplicated values in the titles of the movies which I had to drop
I prepared each data frame separately and studied the data across all the three to find the primary keys I will use to Join them so I can explore them as one data set.

I also added a column Gross_income which is the sum of domestic_gross and foreign_gross because the client did not specify his target market.

For the first table I merged  imdb.title.basics with  imdb.title.ratings using the column that was common between them, I first made the common an index on each data frame separately and I joined them using Inner join so that we can get rid of the data that won’t match on both data frames due to the difference in row and column lengths otherwise we’d have a lot of missing values.

After joining these two tables and I then joined with the third table and began my analysis.

## Results



## Conclusions

- Based on the analysed data Microsoft should create a genre of films that are adventure, action, sci-fi or comedy. Not only has the data shown that they are the most highly rated but they also the most profitable. It’s a win win really.

- Microsoft can also choose to acquire BV studio which is the most profitable  both in locally and internationally.



