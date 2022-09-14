# Investigate A Movie Dataset


## Dataset

> This project involves the data analysis of movies shows. The dataset source is from "The Movie Database (TMDB)". 
Check the Dataset here: <a href = "https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a_data-set-options/data-set-options.pdf"> Dataset Available in a Google Doc </a>

> The dataset comprises of about 10866 rows and 21 columns. The key features include the director of each movie, keywords, runtime, genres, production companies, release year, taglin, overview, vote count, vote average,
release year, budget and revenue.

## Data Wrangling

> We examine our data in this section, assess its quality, clean it up, and make it available in a high-quality format that was ready for analysis. 

We took the following steps in the wrangling process:
- Load the dateset
- Check the percentage of missing values and dropped columns whose missing values are greater than 70%
- Use mode strategy to fill categorical data with missing values of less than 5%
- Drop duplicated rows
- Replace the zero values in the revenue and budget columns with the mean values

## Summary of Investigations

> In our inestigations, we asked and investigate the following questions:

1. What kind of movie genres yield the highest profit?
  - Drama, Comedy, Action, Horror and Adventure movies are the top 5 genre of which drama movies appear most. However, adventure and science fiction movies gener-
ated the highest profit.

2. What characteristics are linked to the popularity of the movies?
  - The release year of amovie increases its popularity overtime
  - When the budegt on each mvie are grouped by genres, there is a slightly positive relationship with the movie popularity

3. Which director is the most well-known and makes the most money from his films?
  - Investigating the top 10 directors, we discovered that Collin Trevorrow is the most popular one.
  
 


