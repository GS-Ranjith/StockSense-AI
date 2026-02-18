📈 Stock Price Prediction Using GRU (Deep Learning)

This project predicts stock prices using historical market data and a GRU (Gated Recurrent Unit) neural network.
Live stock data is fetched using yfinance, scaled with MinMaxScaler, and modeled using TensorFlow/Keras.

The project demonstrates an end-to-end deep learning workflow for time-series forecasting.

🚀 Project Overview

This project:

Downloads real stock data using Yahoo Finance

Preprocesses and scales the data

Creates sequential datasets

Trains a GRU neural network

Predicts future stock prices

Visualizes actual vs predicted values

It focuses on time-series forecasting using deep learning.

🛠 Technologies Used

Python

NumPy

Pandas

yfinance

TensorFlow / Keras

Scikit-learn (MinMaxScaler only)

Matplotlib

Jupyter Notebook



🧠 Model Used
GRU (Gated Recurrent Unit)

GRU is a type of Recurrent Neural Network designed for sequential data like stock prices.
It learns temporal patterns and trends from historical prices.

📊 Workflow

Import required libraries

Download stock data using yfinance

Select closing price

Normalize data using MinMaxScaler

Create time-series sequences

Split into training and testing sets

Build GRU model

Train neural network

Predict stock prices

Plot actual vs predicted values

