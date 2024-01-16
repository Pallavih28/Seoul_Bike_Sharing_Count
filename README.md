# Seoul Bike Sharing Count Prediction 🚴‍♂️📊

## Problem Statement

### Background 🌆

Seoul, a bustling metropolis, has witnessed a significant rise in the popularity of bike-sharing systems. These systems provide a sustainable and convenient mode of transportation for residents and visitors alike. Understanding and predicting bike rental patterns can contribute to better system management, resource allocation, and overall user experience.

### Objective 🎯

The goal of this machine learning project is to develop an accurate predictive model for Seoul Bike Sharing Counts based on various environmental and temporal factors. By analyzing historical data, we aim to build a model that can forecast the number of rented bikes for future time intervals.

### Dataset 📈

The dataset contains the following variables:

- **Date:** The date of the observation.
- **Rented Bike Count:** The target variable representing the number of bikes rented.
- **Hour:** The hour of the day when the observation was recorded.
- **Temperature (°C):** The temperature in Celsius at the time of observation.
- **Humidity (%):** The humidity percentage at the time of observation.
- **Wind speed (m/s):** The wind speed in meters per second.
- **Visibility (10m):** The visibility in meters.
- **Dew point temperature (°C):** The temperature at which air becomes saturated and dew forms.
- **Solar Radiation (MJ/m2):** The amount of solar radiation received per square meter.
- **Rainfall (mm):** The amount of rainfall in millimeters.
- **Snowfall (cm):** The amount of snowfall in centimeters.
- **Seasons:** The season during which the observation was recorded (e.g., Spring, Summer).
- **Holiday:** Binary variable indicating whether it's a holiday (Yes/No).
- **Functioning Day:** Binary variable indicating whether it's a functioning day (Yes/No).

### Task 📋

Given this dataset, the task is to build a regression model that accurately predicts the number of rented bikes based on the provided features. The model should be capable of handling variations in weather conditions, time of day, and other environmental factors.

### Evaluation 📉

The performance of the models will be evaluated using regression metrics such as Root Mean Squared Error (RMSE), R-squared (R2) metrics. The goal is to minimize the prediction error and improve the accuracy of bike rental predictions.

## Table of Contents
- [Dataset]([#dataset](https://www.kaggle.com/datasets/saurabhshahane/seoul-bike-sharing-demand-prediction/data))
- [Dependencies](#dependencies)
- [Setup](#setup)
- [Usage](#usage)
- [Models](#models)
- [Evaluation](#R2score)
- [Contributing](#contributing)
- [License](#license)

## Dataset
The project uses the Seoul Bike Sharing Demand dataset, which includes information about bike rentals, weather conditions, and other relevant features. The dataset is available at [link to dataset].

## Dependencies
Make sure you have the following dependencies installed:
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Learn
- matplotlib

## Usage
The dataset for this project is taken from Kaggle
link: https://www.kaggle.com/datasets/saurabhshahane/seoul-bike-sharing-demand-prediction/data

## Models
- Linear Regression
- Lasso and Ridge Regression
- Decision Tree
- Random Forest
- KNNRegressor
- XGBoostRegressor
- GradientBoost
- ExtraTreesRegressor

## Evaluation
- The R2 score of 0.93 was achieved by ExtraTreesRegressor Model and Tress based algorithms worked well.
