# Climate Change Impact on Agriculture – Machine Learning Project
## Project Overview

This project explores the impact of climate change on agricultural productivity using machine learning models. It leverages a dataset of 10,000 records across multiple countries, crop types, and climate indicators to predict crop yield (MT per HA).

The project covers data preprocessing, exploratory data analysis (EDA), feature engineering, and model evaluation with various regression techniques.

## Collaboration

This project was developed as a collaborative effort, with team members contributing to data analysis, feature engineering, and machine learning model development.


## Dataset

- Rows: 10,000

- Columns: 15

- Features include:

[Year,Country, Region, Crop_Type

Average_Temperature_C, Total_Precipitation_mm, CO2_Emissions_MT

Crop_Yield_MT_per_HA (Target)

Extreme_Weather_Events, Irrigation_Access_%, Soil_Health_Index

Adaptation_Strategies, Economic_Impact_Million_USD]

### The dataset was preprocessed by handling missing values, encoding categorical variables, and creating interaction features.

## Exploratory Data Analysis (EDA)



- Crop yield trends over time and across countries

- Correlations between climate factors (temperature, precipitation, CO₂) and yields

- Boxplots, scatterplots, and line charts to visualize crop yield distribution

- Crop yield vs adaptation strategies

## Models Used

- Multiple regression models were trained and compared:

- Linear Regression

- Decision Tree Regressor

- Random Forest Regressor

- Gradient Boosting Regressor

- XGBoost

- LightGBM

- Support Vector Regressor (SVR)

- K-Nearest Neighbors (KNN)

## Best Performing Model:

- Gradient Boosting Regressor

RMSE: ~0.82

MAE: ~0.70

R²: ~0.29

## Tech Stack

### Language:
Python

### Libraries: 
NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost, LightGBM



