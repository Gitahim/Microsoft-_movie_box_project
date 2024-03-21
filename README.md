# Title:EXPLORATORY DATA ANALYSIS FOR MICROSOFT'S UPCOMING FILM STUDIO.

## 1.Introduction
Microsoft Studio, a brand-new film production company,has tasked me to undertake research using databases from other seasoned film production firms, like Box Office Mojo, IMDB, Rotten Tomatoes, The MovieDB, and The Numberto give them insights on which movies to produce since it has just been  establishmed recently and the film studio lacks experience in creating quality films that will be commercially successful. To find the films that other production companies utilize to make additional quality films, I will carry out an exploratory data analysis using the imported data from the other studios.


## 1.1 Project Overview/Business understanding
Microsoft aims to be a successful player in the entertainment industry by avoiding the complexities of the film studio industry and starting a new company that will create original video content that will appeal to audiences and maximize revenue.With no prior experience in film production, Microsoft recognizes the need to educate itself on the current landscape of box office performers. This knowledge is critical to the studio's strategic decisions regarding the kinds of films it should produce in order to draw audiences and thrive in the fiercely competitive market,i will carry out an exploratory data analysis using box office mojo data,IMDB,and Rotten Tomatoes data.

# 1.2 Objectives

## 1.2.1 Main objective
To identify the genres of film or films that are currently doing well at the box office in order to examine current trends in the film industry.

## 1.2.2 Specific objectives
1. To examine the present cinematic trends based on Box Office Productions
2. To review the mined data  in order to identify the films that are doing well at the box office.
3. To Translate the results obtained into useful information that Microsoft Studio may utilize to make wise choices for creating high-caliber films.
4. To offer suggestions for the kinds of movies that are most likely to be popular  in future.

# 2. Data Understanding

## 2.1 The Data

This project use data from other seasoned film production firms,the datasets are stored in the 'zippedData' folder which were sourced from:

- Box Office MojoLinks
    - bom.movie_gross.csv
- IMDBLinks
    - im.db
- Rotten TomatoesLinks
    - rt.movie_info.tsv
<img src= "movie_data_erd.jpeg">
## 2.2 Importing the relevant libraries

Begin by importing 
+ pandas, 
+ numpy, 
+ csv
with their aliases
### importing libraries
* import pandas as pd 
* import sqlite3
* import csv
* import numpy as np
### importing data visualisation tools
* import matplotlib.pyplot as plt 
* import seaborn as sns

* %matplotlib inline

### 3.0 Data cleaning
# 3.1 Questions to answer
1. What are the columns?
2. How many observations?
3. Are there missing values?
4. Any duplicates?
use the funcitons below to answer the question
* df.columns - know number of columns
* df.info() - information about the dataset
* df.describe() - get statistics summary
* df.isnull().sum() -give sum of NAN values

## Results
(supported with screenshorts)

```markdown
 ![Top 10 watched movies](https://imgur.com/a/vhd9YZR)
 ```
Drama is the most loved genre among the people,it has the highest number in genre_trend, Then Action genre follows and Adventure come in third.

```markdown
 ![barplot showing movie trends](https://imgur.com/a/MZSYcca)
 ```
The monkey King 3 movie is  leading on world wide gross Earnings.It is doing great worldwide and has the highest foreign gross income of over 11.4 Millions compared to other movies.Back to Burgundy is  following closely at number 2 and Avengers:Infinity has no World gross earnings.

```markdown
 ![popularity of movie based on rating](https://imgur.com/a/qfpmBsx)

Movies rated R are the most popular followed by the ones rated PG-13 and the movies rated G are struggling in the movie market and they came last.
 ```
## Conclusion
The project yield the desired results. The main objective and specific objectives are all satisfied.The results shows that the most loved genre among the people is Drama,the monkey King 3 movie is leading on world wide gross Earnings,and also Movies rated R are the most popular.


## Recommendation
1. I will recommend Microsoft studio to produce more of these listed genres; Drama, Action movies and Adventure since they are the most loved genres and this will attract more audience and in return more revenue to Microsoft Studios.

2. I will recommend microsoft to produce movies like The monkey King 3 movie [2018] since it is doing great worldwide and has the highest foreign gross income of over 11.4 Millions,which translates to more money to the company as compared to producing the other movies

3. I will recommend Microsoft studio to produce movies rated R or rated PG-13 since they are the most consumed and this in turn bring money to the company




