# Netflix Content Library — Exploratory Data Analysis

## Project Overview

This project explores Netflix's movie and TV show catalog using Python and Exploratory Data Analysis (EDA). It examines content types, release and addition trends, country representation, genres, ratings, runtimes, and seasons.

## Objectives

- Understand the distribution of Movies and TV Shows.
- Explore how Netflix's catalog grew over time.
- Identify countries contributing the most titles.
- Analyse popular genres and content ratings.
- Investigate movie runtimes and TV show seasons.
- Summarise insights and limitations from the dataset.

## Dataset

The analysis covers **8,807 titles** and **12 columns**, with release years spanning 1925–2021.

Key columns include:

- `show_id`
- `type`
- `title`
- `director`
- `cast`
- `country`
- `date_added`
- `release_year`
- `rating`
- `duration`
- `listed_in`
- `description`

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Data cleaning and feature engineering
- Exploratory data analysis and visualisation

## Data Preparation

The analysis includes:

- Converting `date_added` to datetime.
- Checking missing values and duplicate records.
- Correcting three stand-up specials with runtime stored in the rating field.
- Creating year, month, duration, and content-lag features.
- Separating multi-value country, genre, director, and cast fields for further analysis.

## Key Findings

- Movies account for approximately 69.6% of the catalog, compared with 30.4% for TV Shows.
- Catalog additions peaked in 2019, with 2,016 titles added.
- The United States leads in country representation, followed by India and the United Kingdom.
- International Movies and Dramas are among the most frequent listed genres.
- TV-MA and TV-14 account for a substantial share of catalog ratings.
- Approximately 67% of TV Shows have one season.

## Limitations

The dataset is a catalog snapshot through 2021. It does not provide actual viewing figures, watch time, revenue, acquisition costs, or production costs. Missing metadata and multi-country or multi-genre titles also affect interpretation.

## Project Files

- `Netflix_EDA.ipynb` — Notebook containing exploratory analysis.
- `Netflix_Data_Analysis.pptx` — Presentation summarising the findings.

## Conclusion

This project demonstrates how data cleaning, feature engineering, and exploratory visualisation can help explain the composition and evolution of a streaming content library.

**Project type:** Exploratory Data Analysis  
**Domain:** Entertainment Analytics
