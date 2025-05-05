# Stock-Price-Prediction
This project is a simple stock price predictor that uses historical stock data of Boeing (BA), retrieved via Yahoo Finance. It leverages Linear Regression to model and predict the stock's closing price based on features such as open, high, low, and volume.

Features
Fetches and caches historical stock data (db.csv)
Visualizes stock trends and relationships (Open vs Close, High vs Close)
Trains a linear regression model to predict the Close price
Evaluates model accuracy with an R² score
Compares actual vs. predicted prices over time
Allows for manual predictions with custom input

Technologies Used
Python
yfinance - for downloading stock data
pandas - for data manipulation
matplotlib - for plotting graphs
scikit-learn - for linear regression and model evaluation

