# 📈 Stock Market Analysis & Prediction

## Overview
This project analyzes the stock market performance of four major tech companies—Apple (AAPL), Google (GOOG), Microsoft (MSFT), and NETFLIX (NFLX)—over a four-month period (February to May 2023). It leverages Exploratory Data Analysis (EDA) to uncover trends and uses a Gradient Boosting Regressor model to forecast adjusted closing prices.

## Key Objectives
1. **Data Cleaning:** Check for null values, handle date formatting, and create new temporal and financial features such as Daily Price Range.
2. **Exploratory Data Analysis (EDA):** Visualize historical closing price trends, volume distribution, price volatility (ranges), and correlation among features.
3. **Machine Learning:** Train and hyper-tune an ensemble boosting model (`GradientBoostingRegressor`) using `RandomizedSearchCV` for accurate price prediction.

## Tech Stack
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, SciPy
- **Models:** Gradient Boosting Regressor, hyperparameter tuning with RandomizedSearchCV

## Findings
- Uncovered distinct price and volume patterns (e.g., NFLX showing high price volatility with lower volume, whereas AAPL and GOOG trade at higher volumes).
- The Gradient Boosting Regressor achieved high accuracy and a strong $R^2$ score in predicting adjusted stock prices based on historical metadata.

