# 3. Air Quality in Nairobi

## Project Overview

This project focuses on forecasting air quality by predicting PM2.5 (particulate matter) levels using time series analysis techniques. The dataset consists of air quality sensor measurements collected in Nairobi, Kenya.

The project involves extracting data from a MongoDB database, cleaning and preparing time series data, building forecasting models, and improving model performance through hyperparameter tuning.

## Skills Demonstrated

* Data extraction using MongoDB and PyMongo
* Data cleaning and preprocessing
* Time series analysis
* Exploratory data analysis (EDA)
* Feature engineering for temporal data
* Model evaluation and validation
* Hyperparameter tuning
* Forecasting air quality metrics

## Learning Outcomes

Throughout this project, I learned how to:

* Connect to a MongoDB database and retrieve sensor data
* Clean and wrangle air quality datasets
* Extract and analyze PM2.5 measurements
* Build simple linear regression models
* Develop autoregressive (AR) models
* Build and optimize ARMA models
* Tune model hyperparameters for improved forecasting performance
* Evaluate predictions using time series metrics

## Final Assignment: Dar es Salaam Air Quality Forecasting

For the final project, I:

* Extracted PM2.5 sensor readings from a MongoDB database
* Removed outliers and cleaned the dataset
* Resampled observations into hourly averages
* Visualized time series trends and rolling averages
* Used autocorrelation (ACF) and partial autocorrelation (PACF) plots
* Split data into training and testing sets
* Established and evaluated a baseline model
* Tested multiple autoregressive models to identify optimal hyperparameters
* Analyzed residual distributions
* Performed walk-forward validation
* Compared actual and predicted PM2.5 levels using visualizations

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* PyMongo
* Statsmodels
* Scikit-Learn

## Key Question

**Can historical PM2.5 measurements be used to accurately forecast future air pollution levels?**

## Key Concepts

* Time Series Analysis
* Autoregressive Models (AR)
* ARMA Models
* Hyperparameter Tuning
* Forecasting
* Walk-Forward Validation
* Residual Analysis
* MongoDB Data Extraction

## Repository Structure

* `notebooks/` – Project notebooks
* `data/` – Dataset files
* `images/` – Visualizations and charts
* `README.md` – Project documentation

## Reflection

This project strengthened my understanding of time series forecasting and working with databases such as MongoDB. It reinforced the importance of understanding data structure, careful preprocessing, and model evaluation before focusing on algorithm selection.

## Author

Yogesh Kumar

Applied Data Science Lab — WorldQuant University
