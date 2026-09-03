# Weather Prediction using PyTorch

This project implements deep learning models in PyTorch for predicting the next day's maximum temperature using historical weather data.

# Project Objective

The objective is to use weather information from the previous 14 days to predict the maximum temperature (`TMAX`) of the next day.

# Dataset

The main features used for prediction are:

- `PRCP` – Precipitation
- `TMAX` – Maximum temperature
- `TMIN` – Minimum temperature

# Data processing

1. Loading the weather dataset using Pandas
2. converting the data into pytorch
3. Splitting the data chronologically into:
   - 70% training data
   - 15% validation data
   - 15% test data
4. models used fully connected layers and LSTM
5. undergoes training, validation and testing.


# Evaluation Metrics

The models are evaluated using:

## Mean Absolute Error (MAE)

MAE represents the average absolute difference between the predicted and actual temperatures.

Lower MAE indicates better prediction accuracy.

## Root Mean Squared Error (RMSE)

RMSE measures prediction error while giving larger errors a greater penalty.

Lower RMSE indicates better model performance.


