# Stock Market Sentiment & Market Cap Analysis
A comprehensive data science project focused on analyzing stock price movement predictions using machine learning models and evaluating live market capitalizations of major stocks and indices.

Overview
This project performs historical stock data analysis and price movement prediction for individual stocks (like AAPL) and market indices (like NASDAQ 100, represented by ^NDX). It leverages machine learning models to classify whether a stock’s closing price will go up or down the next day based on recent trading data.

Additionally, the project fetches live market capitalization data from Yahoo Finance for a selection of stocks and visualizes their relative market weights with intuitive pie charts.

Features
Historical Data Loading: Automatically downloads and processes 10 years of historical stock price data with a 5-day interval using the yfinance API.

Feature Engineering: Calculates daily price changes and creates target variables for predicting next-day price movement.

Model Training & Evaluation: Trains and evaluates multiple classification models:

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Models are evaluated using accuracy scores and classification reports on hold-out test data.

Buy/Sell Recommendation: Provides actionable buy or sell/hold recommendations based on the latest prediction from the Random Forest model.

Live Market Capitalization Analysis:

Fetches live market caps for individual stocks and the NASDAQ 100 index (estimated by summing component caps).

Identifies missing data and handles exceptions gracefully.

Visualization:

Pie charts displaying market cap weights of selected stocks.

Bar charts comparing model accuracy across stocks and indices.
