# Netflix Movies And Tv Shows

# Introduction 

Netflix is an American subscription video on-demand over-the-top streaming service owned and operated by Netflix, Inc. The service primarily distributes films and television series produced by the media company of the same name from various genres, and it is available internationally in multiple languages.
This report focuses on netflix viewer preferences across the globe, the patterns of when movies and TV shows are added to the platform, and aims to examine Netflix's content acquisition decisions.

# Data source 
The dataset was accessed from Kaggle. It consists of listings of all the movies and tv shows available on Netflix from 2008 till 2021, along with details such as - cast, directors, ratings, release year, duration, etc. You can view the dataset <a href ="https://www.kaggle.com/datasets/shivamb/netflix-shows">here</a>

# Data cleaning
The dataset is of very good quality there were barely any data quality issues. 
First i checked for duplicate values, there were none but i noticed there were some missing values in the column. Since the number of blanks were few so i replaced the empty columns with the most common country.
There were also issues with the date added column. Some dates had months which were recorded using words others with numbers, some others even followed a different date format. Majority of the dates were recorded using the mm-dd-yy so i converted those recorded in other formats to that format, i also changed the months in words to numbers.

# Insights

## Movies vs TV Shows
Most of the content on netflix now are movies

![image](https://github.com/0layiw0la/netflix-movies-and-tv-shows/assets/103042427/c82a14e4-f1ef-4759-a513-8a8d3f10a2e4)

We can see generally Netflix has more movies than tv shows but now lets consider it by country.

