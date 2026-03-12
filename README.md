# ⛽ Petrol Price Prediction using Machine Learning

## Project Overview

Petrol prices fluctuate due to multiple economic and geopolitical factors such as crude oil prices, currency exchange rates, taxation policies, and fuel demand.

This project uses Machine Learning and Time Series Forecasting techniques to analyze historical fuel price data and predict future petrol prices for the year 2027.

The model identifies patterns in historical trends and generates predictions using statistical forecasting techniques.

## Objective

The goal of this project is to:

Analyze historical petrol price trends

Build a machine learning model for forecasting fuel prices

Predict petrol price trends for future years (2026–2027)

Visualize predictions using data visualization techniques

## Dataset

The dataset used in this project is a synthetic dataset generated for machine learning experimentation.

Dataset Features

Feature	Description

Date	Daily petrol price record

Crude_Oil_Price_USD	Global crude oil price per barrel

USD_INR	USD to INR exchange rate

Demand_Index	Fuel demand indicator

Tax_Rate	Government tax percentage

Petrol_Price_INR	Petrol price per liter

## Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Statsmodels

## Machine Learning Model

This project uses the ARIMA (AutoRegressive Integrated Moving Average) model for time series forecasting.

Why ARIMA?

ARIMA is widely used for:

Time series forecasting

Trend analysis

Economic prediction models

## Project Workflow

1️⃣ Data Collection

2️⃣ Data Cleaning and Preprocessing

3️⃣ Exploratory Data Analysis (EDA)

4️⃣ Time Series Modeling (ARIMA)

5️⃣ Model Training

6️⃣ Petrol Price Forecasting

7️⃣ Prediction Visualization

## Model Performance

The model performance was evaluated using Mean Squared Error (MSE).

Example result:

Mean Squared Error: 59.05
RMSE ≈ 7.68

### This means the model predictions are on average within ₹7–₹8 of actual petrol prices.

## Future Prediction

The trained model forecasts petrol prices up to 2027.

Example prediction:

Date	Predicted Petrol Price
2027-12-14	₹142.50
2027-12-15	₹143.54
2027-12-16	₹144.15

The model predicts petrol prices may range around ₹140–₹145 per liter by late 2027.

## Visualization

The project generates visualizations including:

Historical petrol price trends

Actual vs predicted price comparison

Future petrol price forecasts
