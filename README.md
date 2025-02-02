# Time Series Forecasting

This project explores the concept of time series forecasting using a sample dataset. The dataset contains several features such as DEWP, TEMP, PRES, Iws, Is, Ir, and datetime. The target feature is PM2.5 concentration.

## Project Overview

The goal of this project is to analyze and forecast future PM2.5 readings based on historical data.

## Steps to be Implemented

1. **Data Preprocessing**: Clean and preprocess the dataset to prepare it for analysis.
2. **Exploratory Data Analysis (EDA)**: Perform EDA to understand the distribution of PM2.5 readings and identify any patterns or trends.
3. **Feature Engineering**: Extract relevant features from the dataset to improve the accuracy of the forecasting model.
4. **Model Selection**: Select a suitable time series forecasting model based on the characteristics of the dataset.
5. **Model Training**: Train the selected model using the preprocessed dataset.
6. **Model Evaluation**: Evaluate the performance of the trained model using metrics such as mean absolute error (MAE) and mean squared error (MSE).
7. **Forecasting**: Use the trained model to forecast future PM2.5 readings.

## Dataset Description

The dataset contains 

* Input features (like temperature and humidity)
* The target variable (pm2.5), which will be predicted
* Each row represents one hour of data

## Dependencies and Modules

* Python 3.11.2
* Pandas
* NumPy
* tensorflow
* Matplotlib
* Scikit-learn
* LSTM
* Sequential
* Bidirectional
* Dropout
* BatchNormalization