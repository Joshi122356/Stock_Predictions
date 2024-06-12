# Stock_Predictions
Stock Price(Investment) Prediction Web Application
Description:
The Stock Price (investment)Prediction Web Application is a tool developed using Streamlit Framework
and Python to predict not only future stock prices but also provide Actual value based on historical data. It utilizes machine learning techniques,
particularly the XGBoost regressor, to forecast stock prices and provides users with insights into potential investment opportunities. 
This README provides a detailed guide on setting up and using the application.

Advantages:
Fetch Historical Stock Data: Retrieve historical stock data from Yahoo Finance API.
Data Preprocessing: Perform feature engineering to create relevant features for model training.

Model Training: Train an XGBoost regression model using historical stock data.
Prediction Visualization: Visualize actual and predicted stock prices using interactive charts.

Ticker Information: Fetch detailed information about a specific stock ticker, including sector, industry, market cap, etc.

Platform 
Pycharm
Requirements
Python 3.x
Streamlit
yfinance
pandas
xgboost
matplotlib
nstallation

Clone this repository:
git clone https://github.com/username/stock-price-prediction-web-app.git
Navigate to the project directory:
cd stock-price-prediction-web-app
Install dependencies:
pip install -r requirements.txt
Usage
Run the Streamlit web application:
streamlit run app.py
