# Movies_Capstone_Project
## Project Title: Movie Dataset Exploration and Visualization

Objective:

This project aims to explore various aspects of movie data, such as genres, ratings, director popularity, and release year trends. By utilizing data visualization techniques, we aim to uncover valuable insights and create interactive dashboards that can be used to recommend movies based on user preferences.

### Data Collection
- Dataset: [[Link to the Kaggle: (https://www.kaggle.com/datasets/danielgrijalvas/movies)]
- Key Information: The dataset includes the following key information:
  - Movie titles
  - Genres
  - Ratings
  - Directors
  - Release years
  - Box office performance
  Data Exploration and Analysis
1.  Data Cleaning and Preparation:

- **Handling Missing Values**: Imputed missing values in rating, released, score, votes, writer, star, country, budget, gross, company, and runtime columns using appropriate techniques (like median for numerical columns, mode for categorical columns).
- **Data Formatting**: Ensured data consistency and correct data types.
- **Outlier Detection**: No significant outliers were identified.
2. Exploratory Data Analysis (EDA):

- Genre Analysis: Identified Comedy as the most popular genre, followed by Action and Drama. Analyzed genre trends over time and found a growing popularity for Adventure and Animation.
- Rating Analysis: Explored the distribution of ratings, identified the highest-rated movies, and observed a general trend towards higher ratings in recent years.
- Director Analysis: Analyzed director popularity based on average box office gross and identified Anthony Russo as the top director.
- Release Year Analysis: Analyzed the distribution of release years and observed a general upward trend in average box office gross, with fluctuations in the number of movies released.

### Dashboard Creation (Using Tableau)
1. Data Connection: Connected Tableau to the cleaned and prepared dataset.
2. Data Exploration and Visualization:
 - Created interactive dashboards to visualize key findings, including genre popularity over time, rating distributions, director popularity, and box office trends.
 - Utilized bar charts, line charts, and histograms to represent different data aspects.
 - Designed dashboards to be user-friendly and informative.
3. Dashboard Features:
 - Included interactive elements like filters, drill-down capabilities, and tooltips to enhance user engagement.
 - Considered adding features for movie recommendations based on user preferences.
   
### Project Structure
 - Data Folder: Contains the cleaned dataset (movies.csv).
 - Notebook: Jupyter Notebook with the code for data exploration, analysis, and visualization.
 - Dashboard: Tableau dashboard file (movie_dashboard.twbx).
-  README.md: This document.
  
### Tools and Libraries
 - Python
 - Pandas
 - Matplotlib
 - Tableau

### Challenges and Solutions
 - Missing Data: Handled missing values using appropriate imputation techniques.
 - Data Cleaning: Ensured data consistency and corrected data types.
   
