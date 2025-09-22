# Netflix Titles Dataset

## Overview
This repository contains a cleaned and processed dataset of movies and TV shows available on Netflix. The dataset includes metadata such as titles, directors, cast, country of origin, dates added, release years, content ratings, durations, genres, and descriptions.

## Dataset Description
The dataset consists of the following columns:

| Column Name   | Description                                             |
| ------------- | ------------------------------------------------------- |
| show_id       | Unique identifier for each title                        |
| type          | Content type (Movie or TV Show)                         |
| title         | Title of the movie or TV show                           |
| director      | Director(s) of the title                                |
| cast          | Main cast members                                       |
| country       | Production countries                                    |
| date_added    | Date when the title was added to Netflix                |
| release_year  | Year the title was released                             |
| rating        | Content rating (e.g., PG-13, TV-MA)                     |
| duration      | Length of movie or number of seasons for TV shows      |
| listed_in     | Genres and categories assigned to the title            |
| description   | Brief synopsis or description of the content            |

## Data Cleaning Steps
- Imported raw data from CSV into Excel Power Query.
- Converted the `date_added` column to a proper date format.
- Trimmed whitespace and cleaned text columns using Power Query functions.
- Standardized text casing to lowercase where applicable.
- Removed duplicate and blank rows.
- Ensured correct data types for each column.
- Final cleaned dataset saved for analysis.

## Usage
This dataset can be used for:
- Analyzing content trends over time.
- Investigating distribution of content ratings.
- Exploring genre popularity.
- Building recommendation systems.
- Text analysis of descriptions or cast information.

## How to Use
1. Open the cleaned Excel file (e.g., `netflix_titles_cleaned.csv`).
2. Use Excel filtering, formulas, or visualization tools to analyze the data.
3. Alternatively, import the dataset into Python or other tools for machine learning or statistical analysis.

## Contact
For questions, feedback, or collaboration, please contact: [vadlakondavaishnavi2003@gmail.com]

---

*This README was generated to accompany the Netflix Titles dataset cleaning and analysis project.*
