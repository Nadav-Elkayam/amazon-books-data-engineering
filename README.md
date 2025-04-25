# 📚 Amazon Books Data Engineering & Analysis

This project performs in-depth analysis and processing on Amazon book data, including statistical computations, data cleaning, feature extraction, and visualization.  
It combines data engineering techniques with data science workflows to uncover insights about pricing, weight, dimensions, review patterns, and category classification.

## 📊 Features

- 🧹 Data Cleaning & Transformation:
  - Extracting structured dimensions and converting weights (lbs/oz)
  - Handling missing data for volume, price, and weight

- 📈 Exploratory Data Analysis:
  - Histograms and scatter plots for prices, pages, weight, volume
  - Skewness detection using mean vs median

- 📑 Data Categorization:
  - Book topic classification by keywords in titles
  - Case-insensitive keyword matching across 7 core categories

- 📐 Statistical Analysis:
  - Pearson correlation (volume vs. price)
  - Confidence intervals on price
  - Empirical vs theoretical distribution comparison using normal sampling

## 🧰 Technologies

- Python 3
- pandas
- matplotlib
- seaborn
- numpy
- statistics.NormalDist

## 🗂 Files

- `amazon_books_data.csv` – Main dataset with book info
- `amazon_books_data_pipeline.py` – The main Python script
- `README.md` – Project overview and documentation
