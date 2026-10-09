# Netflix Movies & TV Shows Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset using Python. The goal is to understand content distribution, release trends, ratings, countries, genres, and data quality.

## Objectives

* Explore the Netflix dataset and understand its structure.
* Identify missing values and duplicate records.
* Clean data for better analysis.
* Analyze movies versus TV shows.
* Explore release-year trends, ratings, countries, and genres.
* Discover meaningful insights using data visualization.

## Dataset

The dataset contains **8,807 records and 12 columns**.

**Dataset source:** [Netflix Movies and TV Shows Dataset — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

### Main Columns

* `show_id` — Unique ID for each title
* `type` — Movie or TV Show
* `title` — Title name
* `director` — Director name
* `cast` — Cast members
* `country` — Country of production
* `date_added` — Date added to Netflix
* `release_year` — Year released
* `rating` — Content rating
* `duration` — Movie length or number of seasons
* `listed_in` — Genres and categories
* `description` — Short description of the title

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook
* GitHub

## Project Workflow

1. Import Python libraries.
2. Load the dataset.
3. Explore dataset shape, columns, and sample records.
4. Review data types and statistical summaries.
5. Identify missing values and duplicate records.
6. Clean and prepare the data.
7. Perform univariate, bivariate, and multivariate analysis.
8. Create charts and visualizations.
9. Summarize key findings.

## Key Findings

* The dataset contains **8,807 titles**.
* Movies: **6,131**.
* TV Shows: **2,676**.
* Movies represent approximately **69.6%** of the dataset.
* TV-MA is the most frequent content rating, appearing **3,207 times**.
* The United States is the most frequently listed country, appearing **2,818 times** in the country column's top-value summary.
* The median release year is **2017**.
* The dataset contains missing values, particularly in the director, cast, and country columns.
* Data cleaning is important before performing deeper analysis.

*Note: These findings describe the supplied dataset, not necessarily Netflix's current catalog.*

## Skills Demonstrated

* Data Exploration
* Data Cleaning
* Missing-Value Analysis
* Descriptive Statistics
* Data Visualization
* Exploratory Data Analysis (EDA)
* Python Data Analysis Libraries

## Conclusion

This project demonstrates how Python can be used to explore a real-world dataset, identify data-quality issues, visualize patterns, and communicate useful insights. It provides practical experience in data analysis and supports further learning in Data Science.

## Author

**Sarfaraz Ali**

BS Information Technology Student

## Project Purpose

Created for learning, practice, and portfolio development in Data Analysis and Data Science.
