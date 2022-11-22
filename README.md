# udacity-investigate-a-dataset

# Udacity Data Analyst Project: Investigate a Dataset (TMDb movie data)

In this project, I analyzez a dataset and communicated my findings about it. I used the Python libraries NumPy, Pandas, and Matplotlib to do the analysis

This Python script is written for Project 3 (Term 1) of Udacity's Data Analyst Nanodegree (DAND) and is used to explore TMDb movie data. But what determines if a movie is considered as good or bad? There could be several factors influencig the quality of a movie, as for example the budget, genre, etc. This little project helped the author to improve his data analytics skills and explore some of the success criteria for movies.

First some Data Wrangling was applied, before the data was cleaned in order to perform Exploratory Data Analysis.

# How to run the script
You can run the script using a Python integrated development environment (IDE). This script is written in Python 3, so you will need the Python 3.x version of the installer. The code was written in Jupyter Notebook.


# Datasets
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

Variables:
- id
- imdb_id
- popularity
- budget
- revenue
- original_title
- cast
- homepage
- director
- tagline	
- keywords
- overview
- runtime
- genres
- production_companies
- release_date
- vote_count
- vote_average
- release_year
- budget_adj
- revenue_adj

# Files
- tmdb-movies.csv

# Questions to answer
- Which movie genres are most popular from year to year?
- What is the average runtime of all the movies?
- Which movies had most and least profit?
- Which year had the most profitable movies?
- Which actors had the most appearances in films?

# Findings
The first research question "Which genres are most popular from year to year?" has shown surprising results, as the top ten most popular genres which were drama, comdey, thriller, action, romance, horror, adventure, crime, scienc-fiction and family with a frequency between 1000 to 5000. The least popular movie genres which were foreign, tv-movie and western had frequencies less than 200

The second research question which looked at "What is the average runtime of all the movies?" also shows interesting results. The average runtime of all the movies was approximately 102 minutes. A further analysis into the research question showed that a greater number of movies in our data had runtimes between 80 and 150 minutes. With about approximately 3400 to almost 6800 movies falling within this range. A look at the relationship between the average runtime and the revenue or profits made also showed moives that had runtimes between 80 to about 200 minutes recorded the most revenue or profits.
 
The third research question "Which movies had the most and least profit?" showed some interesting results. Although a higher revenue guaranteed a higher profit, the budget for a movie did not guarantee same. The results of the research question showed that the movie with the highest profit had a lesser budget compared to the movie with the least profit made, which had a much higher budget surprisingly.

The forth research question "Which year had the most profitable movies?" indicate that the year 2015 had movies making the most profits. The findings into the research question showed a steady upward trend in profits made from 1960 onwards, with a few downward trends in profits observed between 1990 and 2000. It has to be considered that the line chart does not show accurate results, as many rows from the original dataset were dropped.

The fifth research question "Which actors had the most appearances in films?" reveals that among all the actors in all the movies in our dataset, Robert De Niro had the most appearances with respect to the top 20 actors in our dataset. With a total of 72 appearances, followed closely by Samuel L. Jackson with a total of 71 appearances and Meryl Streep having the least number of 44 appearances in the top 20 actors in the dataset.

It must be stated that all results are limited to the underlying dataset and as no advaned statistics were performed, the results can only be treated as indicators and are not generalizable. Furthermore, one has to consider that many entries in the dataset have been removed due to missing data.
