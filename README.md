# Exploratory Data Analysis on Home Prices Dataset

This project performs an **Exploratory Data Analysis (EDA)** on a **home prices dataset**. The goal is to clean, analyze, and visualize various features to understand their relationships with home prices (`SalePrice`). This analysis will help us identify the key features that affect home prices.

## Project Overview

This notebook explores a dataset containing various features about homes (such as size, quality, and location) and their sale prices. We perform several tasks:
- **Data Cleaning**: Handle missing values, remove irrelevant features, and handle outliers.
- **Data Exploration**: Generate statistics and visualizations (histograms, boxplots, scatter plots, heatmaps).
- **Correlation Analysis**: Understand the relationships between different features and the target variable (`SalePrice`).

## Data Description

The dataset contains 79 explanatory variables describing various aspects of residential homes. The key variables include:
- `SalePrice`: The target variable representing the sale price of the home.
- `GrLivArea`: Above ground living area.
- `OverallQual`: Overall material and finish quality.
- `GarageCars`: Number of cars that fit in the garage.
- `YearBuilt`: The year the house was built.

For the full list of features and more detailed data descriptions, refer to the dataset documentation.

**Data Source**: [Ames Housing Data on Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## Steps and Analysis

1. **Load the Data**: Load the dataset into a pandas dataframe and preview the first few rows.
2. **Handle Missing Data**: Check for missing values and visualize their distribution.
3. **Visualizations**: 
   - Histograms for `SalePrice` to visualize the distribution.
   - Boxplots for detecting outliers.
   - Heatmap for correlation analysis.
4. **Correlation Analysis**: Investigate the correlation between `SalePrice` and other numeric features.
5. **Outlier Detection**: Identify and remove outliers based on the interquartile range (IQR).
6. **Data Cleanup**: Remove irrelevant and multicollinear features that do not contribute meaningfully to the analysis.

## Visualizations

The project includes the following visualizations:
- **Histograms**: Visualize the distribution of `SalePrice` and other numeric features.
- **Boxplots**: Detect and visualize outliers in features like `SalePrice`, `OverallQual`, etc.
- **Heatmaps**: Show correlations between features and identify highly correlated variables.
- **Scatter Plots**: Display relationships between `SalePrice` and key numeric features like `GarageCars` and `GrLivArea`.

## Technologies Used

- **Python**: The main programming language used.
- **Libraries**:
  - `pandas` for data manipulation.
  - `matplotlib` and `seaborn` for data visualization.
  - `numpy` for numerical operations.
- **Jupyter Notebook**: For creating and running the interactive analysis.

