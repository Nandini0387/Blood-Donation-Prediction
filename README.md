# Blood Donation Prediction

This project aims to predict whether an individual donated blood in March 2007 using data from the Blood Transfusion Service Center. The analysis and prediction are performed using various data processing techniques, exploratory data analysis (EDA), and machine learning with the XGBoost algorithm.

## Project Overview

The main goal of this project is to build a predictive model that can determine if a person donated blood in a given period based on historical data. The project includes the following steps:

1. Data loading and preprocessing
2. Exploratory data analysis (EDA)
3. Data preparation and feature scaling
4. Model training using XGBoost
5. Model evaluation and hyperparameter tuning
6. Saving the trained model

## Data

The dataset used in this project is provided by the Blood Transfusion Service Center Data Set from the UCI Machine Learning Repository. It includes the following features:

- **Recency (months)**: Months since the last donation
- **Frequency (times)**: Total number of donations
- **Monetary (c.c. blood)**: Total blood donated in cubic centimeters
- **Time (months)**: Months since the first donation
- **whether he/she donated blood in March 2007**: Target variable (1 if the donor donated blood in March 2007, 0 otherwise)

## Requirements

To run the code, you need the following Python libraries:

- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost
- joblib

You can install the required libraries using pip:

```bash
pip install pandas matplotlib seaborn scikit-learn xgboost joblib
