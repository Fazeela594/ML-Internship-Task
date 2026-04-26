# Task 2: Stock Price Prediction 

## Objective
The objective of this task is to predict the next day's stock closing price using historical stock market data and machine learning techniques.

## Dataset Used
- Source: Yahoo Finance
- Library: yfinance (Python API)
- Stock used: Apple Inc. (AAPL)
- Time Period: 2020 - 2025

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yfinance
## Features Used
The model uses the following features:
- Open price
- High price
- Low price
- Volume
## Target Variable
- Next day's Closing Price (Shifted Close column)
##  Machine Learning Model
- Linear Regression

##  Steps Performed

### 1. Data Collection
- Historical stock data was fetched using the yfinance API.

### 2. Data Preprocessing
- Selected relevant features (Open, High, Low, Volume, Close)
- Removed missing values
- Created target variable using shift(-1)

### 3. Train-Test Split
- Dataset was split into training and testing sets
- Time series order was maintained (shuffle=False)

### 4. Model Training
- Linear Regression model was trained on historical data

### 5. Prediction
- Model predicted next-day closing prices

### 6. Visualization
- Actual vs Predicted stock prices were plotted using Matplotlib

##  Results
- The model successfully captures overall stock price trends.
- Predicted values closely follow actual market movement patterns.


## Visualization
- A line graph was used to compare:
  - Actual Stock Prices
  - Predicted Stock Prices

## Key Learnings
- Time series data handling
- Stock market data analysis
- Regression modeling techniques
- API-based data fetching
- Data visualization




## 🔗 Repository
This project is part of AI/ML Internship Tasks.
