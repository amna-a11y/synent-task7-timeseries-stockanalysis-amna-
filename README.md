Time Series Analysis – Stock Price Prediction
Problem Statement

Financial market data changes over time and requires time series analysis to understand trends, volatility, and stock performance. This project analyzes stock prices to identify patterns and market behavior.

Dataset Details

The dataset contains historical stock market data with features such as date, open, high, low, close price, volume, ticker, brand name, industry tag, and country. The analysis focuses on AMZN (Amazon) stock.

Approach

Data preprocessing included date conversion, missing value handling, sorting, and filtering for AMZN stock. Time series preparation involved setting date as index and resampling. Feature engineering included daily returns and moving averages (30-day and 90-day). Statistical analysis was performed using ADF test and ACF. Visualizations were created for trends, returns, and comparisons.

Results

The stock shows a long-term upward trend with moderate volatility. Moving averages confirm stable growth patterns. The ADF test indicates stationarity conditions based on p-value. Overall returns are positive, showing strong performance over time.
