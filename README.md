------------------------------------------------
# Project Title: Netflix Data Visualization
-----------------------------------------------

## Overview:

- This project involves analyzing Netflix data to gain insights into the most watched genres and ratings distribution. 
- The analysis is performed using both Python and R programming languages. 
- The Python script focuses on data extraction, cleaning, and visualization of most watched genres and ratings distribution. 
- The R script focuses on visualizing only the ratings distribution.
----------------------------------------------

## Files:

- **netflix_analysis.py:** Python script for data extraction, cleaning, and visualization.
- **netflix_ratings_distribution.R:** R script for visualizing ratings distribution.
- **netflix_data.zip:** Zip file containing the raw Netflix data.
- **Netflix_shows_movies.csv:** Extracted CSV file used for analysis.
-------------------------------------------------

## Order of Execution:

- Execute netflix_analysis.py in Python first to extract, clean, prepare the data, and visualize.
- Then, execute netflix_ratings_distribution.R in R to visualize the ratings distribution.
-----------------------------------------------

## Requirements:

- Python 3.x with pandas, seaborn, and matplotlib installed.
- R with ggplot2 and dplyr libraries installed.
-------------------------------------------------

## Python Script (netflix_analysis.py) - Steps:

- **Step 1: Data Preparation** 
Extracts 'netflix_data.csv' from 'netflix_data.zip' and renames it to 'Netflix_shows_movies.csv'.
- **Step 2: Data Cleaning**
Loads the dataset and fills missing values in 'director', 'cast', 'country', 'rating', and 'date_added' columns.
- **Step 3: Data Exploration**
Generates basic statistics and descriptions of the data.
- **Step 4: Data visualization**
Visualizes the most watched genres and ratings distribution using seaborn.
-----------------------------------------------------

## R Script (netflix_ratings_distribution.R) - Steps:

- **Step 1: Load the Data**
Loads 'Netflix_shows_movies.csv' into R for analysis.
- **Step 2: Data Cleaning**
Fills missing values in 'director', 'cast', 'country', 'rating', and 'date_added' columns.
- **Step 3: Data Visualization**
Visualizes ratings distribution using ggplot2 in R.
---------------------------------------------------------

## Notes:

- Ensure all files (netflix_analysis.py, netflix_ratings_distribution.R, netflix_data.zip, and Netflix_shows_movies.csv) are in the same directory/folder before running the scripts.
- The extracted CSV file (Netflix_shows_movies.csv) is generated from netflix_analysis.py and used as input for netflix_ratings_distribution.R.
------------------------------------------------------------

