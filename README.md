# Netflix Data Exploration and Visualization

This repository contains the analysis and visualization of Netflix's movie and TV show catalog. The project aims to generate actionable insights that can guide Netflix's content strategy, helping the company make data-driven decisions on content production and distribution.

## Dataset Overview

The dataset includes information on movies and TV shows available on Netflix, such as:
- **Show ID:** Unique identifier for each movie/TV show.
- **Type:** Indicates whether the content is a movie or TV show.
- **Title:** Title of the movie/TV show.
- **Director:** Director of the content.
- **Cast:** Actors involved in the movie/TV show.
- **Country:** Country where the content was produced.
- **Date Added:** Date when the content was added to Netflix.
- **Release Year:** The year the content was originally released.
- **Rating:** Content rating (e.g., TV-MA, PG-13).
- **Duration:** Duration of the movie or number of seasons for a TV show.
- **Genre:** Genre of the content.
- **Description:** A brief description of the content.

## Data Cleaning and Preprocessing

The data required cleaning and preprocessing to handle issues such as:
- **Trailing and Leading Spaces:** Removed using the `strip()` method.
- **Multiple Values in Cells:** Split into individual elements using the `split()` method and expanded using the `explode()` function.
- **Null Values:** Filled with appropriate placeholders like "Unknown Director" or "Unknown Country".
- **Duplicates:** Identified and removed duplicate rows to ensure precise analysis.

## Exploratory Data Analysis (EDA)

The analysis was conducted to uncover key patterns and insights:

### Non-Graphical Analysis
- **Top Directors:** Identified directors who have directed the most movies and TV shows.
- **Top Actors:** Listed actors who have appeared most frequently in movies and TV shows.
- **Top Countries:** Determined the countries that produced the most movies and TV shows.

### Visual Analysis
- **Movies vs. TV Shows:** Bar graph comparing the number of movies and TV shows on Netflix.
- **Release Trends:** Line plots showing the number of movies and TV shows released each year.
- **Week-wise and Month-wise Content Addition:** Bar plots showing when most movies and TV shows were added to Netflix.

### Insights
- **Content Distribution:** Analysis revealed that more movies than TV shows are available on Netflix.
- **Release Trends:** The number of movies and TV shows added to Netflix has been increasing over the years.
- **Top Genres:** International movies and TV shows are the most produced genres on Netflix.
- **Ratings:** The majority of Netflix's content is rated TV-MA, particularly in movies and TV shows.

## Business Recommendations

Based on the analysis, the following recommendations were made:
1. **Focus on Popular Genres:** Increase marketing efforts for popular genres, especially during peak content addition months.
2. **Optimize Content Release:** Leverage data on optimal release months and weeks to maximize viewership.
3. **Target Popular Actors and Directors:** Highlight collections featuring popular actors and directors to attract more subscribers.
4. **Address Low Activity Periods:** Investigate and potentially boost content releases during months with low activity to maintain user engagement.

## How to Run the Analysis

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Netflix-Content-Insights.git
