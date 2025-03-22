# Netflix ETL and Exploratory Data Analysis (EDA)

## Overview
This project performs **Extract, Transform, Load (ETL)** operations and **Exploratory Data Analysis (EDA)** on the Netflix dataset. The analysis helps understand trends in Netflix content, including content distribution, release years, and regional production patterns.

## Features
- **ETL Process:**
  - Extracts data from the Netflix dataset.
  - Cleans and transforms data (handling missing values, data type conversions).
  - Loads processed data for further analysis.
  
- **EDA and Visualization:**
  - Distribution of movies and TV shows.
  - Year-wise content addition trends.
  - Analysis of content duration.
  - Country-wise production distribution.
  - Content age at the time of addition to Netflix.

## Dataset
- **Source:** Netflix Movies and TV Shows dataset.
- **Key Columns:**
  - `type` (Movie/TV Show)
  - `release_year`
  - `date_added`
  - `duration`
  - `country`

## Visualizations and Insights
1. **Movies vs. TV Shows Distribution**  
   - Compares the count of Movies and TV Shows on Netflix.
   
2. **Content Release Year Distribution**  
   - Displays the number of titles released per year.
   
3. **Content Age at Addition**  
   - Shows how old the content was when added to Netflix.
   
4. **Country-wise Content Distribution**  
   - Identifies top 10 content-producing countries.

## Dependencies
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
