# Netflix-Content-Strategy-Analysis

This project explores and analyzes the Netflix dataset to gain insights into the content available on the platform. The analysis covers various aspects such as content type distribution, popular genres, top directors, and release trends over time.

## Dataset
The dataset used in this project contains information on Netflix titles, including the following attributes:
- **show_id**: Unique identifier for each show
- **type**: Type of content (Movie or TV Show)
- **title**: Title of the show
- **director**: Director of the show
- **country**: Country where the show was produced
- **date_added**: Date the show was added to Netflix
- **release_year**: Year the show was released
- **rating**: Rating of the show
- **duration**: Duration of the show (minutes or number of seasons)
- **listed_in**: Genres associated with the show

## Project Structure

The project consists of the following steps:

1. **Data Loading and Overview**: Loading the dataset, displaying the first few rows, and checking data types.
2. **Data Cleaning**:
   - Checking for missing values and duplicates.
   - Converting `date_added` to datetime format for easier analysis.
3. **Exploratory Data Analysis (EDA)**:
   - Distribution of content types (Movies vs. TV Shows) using bar and pie charts.
   - Distribution of ratings with bar and pie charts.
   - Top 10 countries by the number of Netflix titles.
   - Top 15 directors with the most titles on Netflix.
   - Popular genres for movies and TV shows.
   - Monthly and yearly trends in content release.
   - Word cloud of movie titles for a visual overview.

## Key Findings

- **Content Type Distribution**: The majority of Netflix content is TV Shows, with a steady increase in releases over the years. Movies are the second most common type.
- **Popular Genres**: Documentaries, TV Dramas, and Comedies are among the most popular genres.
- **Top Directors**: The directors with the most titles on Netflix are primarily associated with TV Shows.
- **Release Trends**: A significant increase in content releases is observed over the years, with a notable spike in 2021.
- **Word Cloud**: A word cloud of movie titles shows the diversity of content available on Netflix.

## Visualizations

The project includes a variety of visualizations to provide insights into the data:

- **Bar and Pie Charts**: For content type distribution, rating distribution, and country-wise content distribution.
- **Line Charts**: To show monthly and yearly release trends.
- **Word Cloud**: To display popular words in movie titles.

## Conclusion

The analysis provides valuable insights into the content on Netflix. These insights can be used to guide future content development and acquisition strategies, ensuring that Netflix continues to meet the evolving needs and preferences of its subscribers.

