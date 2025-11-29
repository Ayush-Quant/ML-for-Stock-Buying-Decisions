# ML-for-Stock-Buying-Decisions

This project applies various Machine Learning models to assist in stock buying decisions and evaluate their performance compared to actual market returns.
It combines predictive analytics, financial modeling, and portfolio construction to identify which ML model performs best in forecasting stock movements.

🎯 Objectives

Collect daily stock price data of 10 companies from 10 different industries for the last 3 years.

Use a Support Vector Classifier (SVC) to predict stock buying behaviour and compare predicted cumulative returns with actual returns.

Create an equally weighted portfolio and compare its predicted cumulative returns against major indices such as Nifty50 and BSE Sensex.

Implement SARIMAX, Support Vector Regression (SVR), and XGBoost for stock price prediction.

Perform model comparison to identify the most accurate technique.

Introduce CatBoost as an alternative ML model and analyze its performance relative to others.

🧩 Models Implemented
 
SVC (Support Vector Classifier)	for Classification	 

SVR (Support Vector Regression)	for Regression

SARIMAX	Time Series	Forecasting based on past data and exogenous variables	Suitable for trend & seasonality

XGBoost	Ensemble Learning	Regression & prediction	Gradient boosting for improved accuracy

CatBoost	Ensemble Learning	Regression & classification	Handles categorical data efficiently

💡 Dataset

The dataset contains daily stock prices of 10 companies from 10 different industries for the past 3 years.

You can access the dataset here: https://drive.google.com/file/d/1SiYhXjRuvcuwQes3EGas6Qo7ZOn41ZtN/view?usp=drive_link

📊 Results Overview

Comparative performance of ML models shows how different techniques capture stock price movements.

Portfolio-level predictions demonstrate how ML-based decisions perform against real-world indices.

CatBoost and XGBoost tend to yield more stable and higher-accuracy forecasts in certain market conditions.

(Detailed analysis and visuals are included in the Python file.)

 
