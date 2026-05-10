Stock Market Price Prediction — Nifty 50
📌 Project Overview

This project focuses on predicting the closing price of the Nifty 50 index using Machine Learning and Deep Learning techniques. The system analyzes historical OHLCV (Open, High, Low, Close, Volume) market data along with technical indicators to forecast future market trends and support data-driven financial analysis.

The project compares multiple ML and DL models including Linear Regression, Random Forest, XGBoost, SVR, LSTM, GRU, and CNN-LSTM to identify the best-performing prediction model.

🚀 Key Features
Historical Nifty 50 stock market analysis
Technical indicator-based feature engineering
Machine Learning & Deep Learning model comparison
Time-series forecasting pipeline
Real-time prediction architecture design
KPI evaluation using RMSE, MAE, MAPE, and R²
Candlestick chart visualization
REST API deployment concept using Flask/FastAPI
🛠️ Technologies Used
Programming & Data Processing
Python
Pandas
NumPy
Scikit-learn
TensorFlow / Keras
XGBoost
Visualization & Analytics
Matplotlib
Seaborn
mplfinance
Power BI
Deployment & Tools
Flask REST API
Google Colab
GitHub
yfinance API
📊 Dataset Information
Source: Yahoo Finance (^NSEI)
Time Period: January 2019 – May 2026
Total Records: 1,806 trading sessions
Features Used:
Open
High
Low
Close
Volume
SMA
EMA
RSI
MACD
Bollinger Bands
ATR
OBV
Lag Features
🤖 Models Implemented
Machine Learning Models
Linear Regression
Random Forest Regressor
XGBoost Regressor
Support Vector Regression (SVR)
Deep Learning Models
LSTM
GRU
CNN-LSTM Hybrid
📈 Model Performance Summary
Model	RMSE	R² Score
Linear Regression	47.42	0.9980
XGBoost	159.63	0.9776
Random Forest	179.35	0.9717
SVR	221.62	0.9568
CNN-LSTM	312.47	0.8412
GRU	500.30	0.7868
LSTM	520.80	0.7690

🏆 Best Performing Model: Linear Regression

📌 Project Workflow
Data Collection using yfinance API
Data Cleaning & Preprocessing
Feature Engineering
Technical Indicator Generation
Train-Test Split
ML/DL Model Training
Performance Evaluation
Visualization & Forecasting
Next-Day Price Prediction
📷 Visualizations Included
Candlestick Charts
Feature Importance Graphs
Actual vs Predicted Graphs
Training vs Validation Loss Curves
KPI Comparison Charts
🔮 Future Enhancements
Real-time market prediction
Sentiment analysis integration
Cloud deployment with Docker & AWS
Mobile/Web application integration
Portfolio optimization system
Live trading signal generation
▶️ How to Run the Project
Clone the repository
Install required libraries
Open the notebook in Google Colab or Jupyter Notebook
Run all cells sequentially
View predictions and visualizations
