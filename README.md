# Netflix Data Analysis Project

This project involves analyzing a Netflix dataset that contains information about TV shows and movies available on Netflix up to 2021. The dataset was sourced from [Flixable](https://www.flixable.com/), a third-party Netflix search engine, and is publicly available on [Kaggle](https://www.kaggle.com/). The goal of this project is to perform data preprocessing, cleaning, and visualization to answer specific questions about the Netflix catalog.

## Project Overview

In this project, I used the following tools and technologies:
- **Python** for coding and data manipulation.
- **Pandas** for handling and processing the dataset.
- **Seaborn** for visualizing trends and patterns.
- **Jupyter Notebook** for writing and executing code in an interactive environment.

### Dataset Information
The dataset includes various details about the movies and TV shows on Netflix, such as:
- Title
- Director
- Cast
- Country
- Date of release
- Rating
- Duration
- Type (Movie/TV Show)
- Category (Drama, Comedy, etc.)

## Project Workflow

1. **Data Preprocessing**:
   - Imported the necessary libraries and the Netflix dataset.
   - Handled missing values and filled them appropriately.
   - Removed duplicate records.
   - Cleaned the dataset for better analysis.

2. **Data Visualization**:
   - Visualized the data using Seaborn to discover patterns and trends.

3. **Problem-Solving**:
   I answered 15 key questions related to Netflix's content:

   1. Is there any duplicate record in the dataset? If yes, removed the duplicate records.
   2. Are there any null values present? Displayed the missing data with a heatmap.
   3. For "House of Cards", what is the show ID and who is the director of the show?
   4. In which year were the highest number of TV shows and movies released? (Visualized with a bar graph)
   5. How many movies and TV shows are in the dataset? (Displayed with a bar graph)
   6. Show all the movies released in the year 2000.
   7. Display only the titles of all TV shows released in India.
   8. Show the top 10 directors who contributed the most TV shows and movies to Netflix.
   9. Display records where the category is "Movie" and the type is "Comedies" or the country is "United Kingdom".
   10. How many movies or shows feature Tom Cruise?
   11. What are the different ratings defined by Netflix?
   12. How many movies received the 'TV-14' rating in Canada?
   13. How many TV shows received an 'R' rating after 2018?
   14. What is the maximum duration of a movie/show on Netflix?
   15. Which individual country has the highest number of TV shows?
   16. How can we sort the dataset by year?
   17. Find instances where the category is 'Movie' and type is 'Dramas' or the category is 'TV Show' and type is 'Kids' TV'.

## Conclusion

This project provided valuable insights into Netflix's content and allowed me to practice key data analysis techniques.
Through data preprocessing, visualization, and answering specific questions, I explored the diversity and distribution of movies and TV shows across various categories and countries on Netflix.
