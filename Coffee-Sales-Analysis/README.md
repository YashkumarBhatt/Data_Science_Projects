# ☕ Coffee Sales Analysis & Prediction

## Overview
This project analyzes coffee sales from a vending machine over a 7-month period (March-August 2024). The main objective is to understand sales trends based on coffee types, monthly variation, pricing, and purchase methods (cash vs. card). Furthermore, Machine Learning models are employed to predict sales revenue and analyze feature importance.

## Key Objectives
1. **Data Preprocessing & Cleaning:** Handle missing values (e.g., filling nulls in card transactions) and extract useful time-based features like month, year, day of week, and hour.
2. **Exploratory Data Analysis (EDA):** Visualize sales trends, popular coffee types, revenue generation, and peak hours using `matplotlib` and `seaborn`.
3. **Machine Learning:** Train Regression models (Linear Regression and Random Forest Regressor) to predict transaction revenue based on contextual features and compare their performances.

## Tech Stack
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Models:** Linear Regression, Random Forest Regressor

## Findings
- Successfully preprocessed temporal and categorical data.
- Explored revenue distributions among various coffee types.
- Random Forest model effectively captures non-linear relationships to predict revenue accurately, providing insights into top revenue-driving features.

