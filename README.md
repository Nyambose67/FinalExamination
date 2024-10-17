Final Exam: Time Series Forecasting and Sentiment Analysis
Overview
This project implements a machine learning approach to solve two main tasks:

Classification (Predicting Withdrawals): Predict if an employee will withdraw funds from the accessible pot in the next 12 months.
Forecasting (Savings Growth): Forecast the long-term growth of savings in the locked pot using time series forecasting.

Key Concepts:

Classification: Predict withdrawal tendencies using models like logistic regression or decision trees.
Forecasting: Predict future growth of retirement savings using ARIMA.

Datasets and Relevancy
1. Classification Data
Data on employees' withdrawal behavior is used to predict whether they are likely to deplete their savings.
The classification model helps institutions take preventive measures.
2. Forecasting Data
Data related to locked pot savings growth over time.
Time series techniques like ARIMA model future growth.

Project Structure
1. Data Preprocessing
Classification: Handle missing data and preprocess features for modeling.
Forecasting: Handle time series data, including dealing with missing values.

2. Machine Learning Implementation
Classification: Implement logistic regression, and random forest to predict withdrawals.
Forecasting: Apply ARIMA model for locked pot savings predictions.

3. Model Evaluation
Classification: Evaluate models using metrics such as accuracy, precision, recall, and F1-score.
Forecasting: Use Mean Squared Error (MSE) to assess forecasting accuracy.

4. Complexity Analysis
ARIMA: Time complexity is O(n) for each forecasted value.
