# Car Price Prediction

## Overview

Machine learning project to predict automobile prices.
Uses car features such as engine size, horsepower, mileage, fuel type, and body style.
Includes data cleaning, EDA, feature engineering, and regression model evaluation.


## Data Cleaning

Replaced invalid entries (“?”) with missing values.
Converted string-based numeric columns to proper numeric type.
Handled missing values using mean, median, or forward fill.
Removed outliers from engine size, width, and price.
Dropped weakly correlated features.


## Exploratory Data Analysis (EDA)

Used histograms, boxplots, scatter plots, and heatmaps.
Strong price correlations found with engine size, horsepower, curb weight, and width.
Negative correlation observed with city-mpg and highway-mpg.
Compared price variations across car makes, fuel types, and body styles.


## Feature Engineering

Selected relevant features based on correlation.
Encoded categorical variables using OneHotEncoder.Split the dataset into training and testing sets.


## Model Evaluation

Evaluated Linear Regression, Ridge Regression, and Lasso Regression.
Linear Regression showed signs of overfitting.
Ridge Regression provided the best balance between train and test performance.
Lasso performed well but was slightly less stable.
Ridge Regression identified as the most reliable model with r2 score of 86%.


## Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn


## Project Structure

Car Price Prediction/
│
├── Car Price Prediction.ipynb      # Main Jupyter Notebook with full analysis
├── Automobile_data.csv             # Dataset used for the project
└── README.md                       # Project documentation
