# Tesla Stock Price Predictor

## Motivation
The financial markets are dynamic, and accurate stock price prediction is crucial for investors and traders. This project utilizes LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) neural network architectures known for capturing complex patterns in time-series data to enhance stock price prediction accuracy.

## Introduction
Predicting stock prices in the market characterized by dynamic patterns is challenging. Neural networks, specifically LSTM and GRU, are utilized due to their ability to model temporal dependencies and learn from historical data. This project aims to leverage these architectures for forecasting Tesla stock prices.

## Project Overview
### Data Collection and Preprocessing:
- Gathered historical Tesla stock data.
- Split the data into training and testing sets.

### Model Development:
- Implemented LSTM and GRU models for stock price prediction.
- Trained the models using the training dataset.

### Iterative Prediction:
- Made predictions for multiple future time steps using the trained models.

### Performance Evaluation:
- Evaluated model performance using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## Results
### LSTM:
- MSE: 959.709
- MAE: 24.331
- RMSE: 30.979

### GRU:
- MSE: 460.764
- MAE: 17.061
- RMSE: 21.465

## Inference
### Simplicity and Training Speed:
- GRUs have a simpler architecture compared to LSTMs.
- Reduced complexity may lead to easier training and faster convergence.
- Simplicity may contribute to better generalization, particularly with smaller datasets.

## Note
This project was developed in an IPython Notebook using Google Colab.
