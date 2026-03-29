# Data_Science_Assignment-2
<b>👉 <a href="https://colab.research.google.com/drive/1tME-rP6CGxVJuz5DqyjPJD9WWluD6cw4?usp=sharing">Click Here to view the full assignment in Google Colab</a></b
# Movie Dataset Analysis for Production Insights

## Overview
This project explores a dataset of 3,000 movies to provide data-driven recommendations for a rookie movie producer. It analyzes financial metrics, cast and crew trends, and genre popularity to identify what makes a successful film.

## Key Steps & Features
* **Data Exploration & Sanity Checks:** Loaded the dataset and performed initial inspections for missing values, data types, and basic statistics.
* **Data Cleaning:** Wrote custom Python functions using `ast.literal_eval` to extract clean names from complex, list-like text columns (genres, cast, and crew).
* **Financial Calculations:** Computed standard metrics for every movie, including **Profit** (Revenue - Budget) and **Return on Investment (ROI)**.
* **Exploratory Data Analysis (EDA):** Answered specific business questions, including:
    * Identifying the highest-profit movie and its key personnel.
    * Finding the original language with the highest average ROI.
    * Extracting all unique movie genres.
    * Ranking the top 3 producers by average ROI.
    * Deep-diving into the most frequently cast actor's portfolio.
    * Discovering the preferred actors of the top 3 directors.
* **Data Visualization:** Created beginner-friendly charts using `matplotlib` to visualize the top 10 genres, Budget vs. Revenue, and the top 5 languages by ROI.

## Tools & Libraries Used
* Python
* Pandas (for data manipulation)
* Matplotlib (for simple visualizations)
* AST (Abstract Syntax Trees, for parsing stringified lists)
