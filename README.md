Financial Market Prediction Using Machine Learning

This MSc Data Science project evaluates whether machine-learning and deep-learning models can outperform a classical statistical baseline when predicting S&P 500 market direction.

Project Summary

Six forecasting approaches were evaluated on 6,955 daily S&P 500 observations from 2000 to 2026:

ARIMA-GARCH
LSTM
BiLSTM
XGBoost
ARIMA-LSTM hybrid
CNN-LSTM/XGBoost ensemble

The project included 20 engineered technical indicators, multi-seed training, financial backtesting, Diebold-Mariano significance testing and SHAP explainability.

Key Results
ARIMA-GARCH achieved the strongest genuine result with 52.88% directional accuracy.
It significantly outperformed the evaluated ML/DL models (p < 0.0001).
XGBoost achieved a 10-percentage-point advantage over ARIMA during the 2022 bear market.
Automated diagnostic checks identified two failed runs and one collapsed ensemble across 23 stochastic runs.
The findings showed that greater model complexity did not necessarily improve forecasting performance.
Technologies

Python, Pandas, NumPy, scikit-learn, TensorFlow, Keras, XGBoost, statsmodels, SHAP, Matplotlib and Seaborn.
