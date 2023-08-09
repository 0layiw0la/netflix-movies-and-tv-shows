# Netflix Movies And Tv Shows

![image](https://github.com/0layiw0la/netflix-movies-and-tv-shows/assets/103042427/2300ea8d-46e0-435b-ad8e-f376edaf4bb3)


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

We can see generally Netflix has more movies than tv shows but now lets consider it by country. Netflix is a global company and as a result gets content from various countries, i will be focusing on the top ten for this analysis.

### Top ten countries
The US, india, and the UK are the three largest content producers for netflix with the US having the largest number. Considering Netflix is an American company it makes sense most of it's content comes from the US.

![image](https://github.com/0layiw0la/netflix-movies-and-tv-shows/assets/103042427/b045ce98-fc68-4b5a-bd23-9d56a080b0a9)  

### Movie & Tv show distribution for the top ten countries

![image](https://github.com/0layiw0la/netflix-movies-and-tv-shows/assets/103042427/e48b88a9-529e-4ad2-9c4d-a165b40d181d)

From this we can see that SOuth korea has alot more series than movies this can be attributed to the popularity of K-dramas, which have gained a massive following worldwide. The preference for TV series over movies in South Korea allows us see the importance of understanding and respecting regional content preferences.
India on the other hand is the complete opposite with over 90% of content being movies, This could be due to bollywoods success worldwide.

### Movies and Tv shows over the years

Netflix became available worldwide in january 2016 and the increase in content acquisition is clear if we look at the graph below. Content addition seems to have slowed down in 2019 this is probably due to Covid-19's effect on the industry which caused a lot of films to pause shooting or postpone release dates.

![image](https://github.com/0layiw0la/netflix-movies-and-tv-shows/assets/103042427/2b1ea761-9dcd-4ac7-b079-fd33ec9c76fc)

## Most Popular Genres
The three most popular genres on Netflix are drama, comedies and action adventure in order.

![image](https://github.com/0layiw0la/netflix-movies-and-tv-shows/assets/103042427/76c885c7-10e2-40cc-9dd3-ebbf222a2acb)

### Viewer Demographics (AGE)
Almost half the content on youtube is restricted to viewers 18 and above with 47% of shows being unsuitable for teenagers and 77% of shows being unsuitable for children. Netflix's target seems the be mostly older people.
![image](https://github.com/0layiw0la/netflix-movies-and-tv-shows/assets/103042427/ebfccb48-1a4f-4830-98bc-1024f76cb1ab)

# Thanks for reading, i hope you enjoyed the report. :smile:

