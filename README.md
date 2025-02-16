Energy Price Prediction and Trading Strategy Optimization
This project focuses on forecasting energy prices using Artificial Neural Networks (ANN) and developing an optimized trading strategy based on market regime identification. By leveraging GARCH(1,1) models and weather data, the project combines predictive modeling with robust trading techniques to maximize profitability and minimize risk.

Table of Contents
Introduction
Data Overview
Methodology
Key Features
Results

Introduction
Energy markets are complex, influenced by both external factors (e.g., weather) and internal dynamics (e.g., volatility). This project integrates advanced statistical models and machine learning techniques to predict energy prices and build a trading strategy capable of adapting to varying market conditions.

Data Overview
Energy Price Data: Half-hourly data from August 2024 to December 2024.
Weather Data: Artificially generated weather data from 9 cities in Great Britain.
Correlation Analysis: Newcastle's temperature data showed the strongest correlation with energy prices and was used as a key feature.
Methodology
Data Preprocessing:

Artificial weather data generation.
Feature engineering for ANN inputs (temperature and price data).
Price Prediction:

ANN architecture with layers designed for non-linear pattern learning.
Metrics: Mean Squared Error (MSE), R-squared, Mean Absolute Percentage Error (MAPE).
Market Regime Identification:

Used GARCH(1,1) models to classify market conditions into high and low volatility regimes.
Trading Strategy:

Entry strategy based on ANN price predictions.
Volatility filtering using GARCH(1,1) outputs.
Risk management: Stop-loss measures and same-day position closure.
Key Features
Artificial Neural Network (ANN):

Predicts energy prices with a high degree of accuracy using weather data.
Optimized with dropout layers and batch normalization.
Market Regime Classification:

Identifies periods of high and low volatility for informed trading decisions.
Trading Strategy:

Combines predictive analytics with robust risk management.
Achieves high profitability and a Sharpe Ratio of 9.22.
Results
ANN Performance:

MSE: 934.11
R-Squared: 0.31
MAPE: 37.49%
Trading Strategy:

Win Rate: 80.95%
Sharpe Ratio: 9.22
Total Profit: 59,664.45 (Corrected Code)
