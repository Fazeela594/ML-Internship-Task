# Task 6: House Price Prediction
## Objective
To build a machine learning model that predicts house prices based on property features such as area, number of bedrooms, bathrooms, and other attributes.

##  Dataset
Housing Dataset (CSV file)

### Features:
- area
- bedrooms
- bathrooms
- stories
- parking
- mainroad
- guestroom
- basement
- airconditioning
- furnishingstatus

### Target:
- price

## Model Used
Linear Regression


## Approach
1. Loaded dataset using pandas
2. Checked data shape, columns, and summary
3. Handled missing values
4. Converted categorical data into numerical form using one-hot encoding
5. Selected features and target variable
6. Split data into training and testing sets
7. Trained Linear Regression model
8. Predicted house prices
9. Evaluated model using MAE and RMSE
10. Visualized actual vs predicted values

## Features of the Project
- Handles categorical and numerical data
- Uses regression for prediction
- Simple and interpretable model
- Visualization of results
## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

##  Example Output
The model predicts house prices and compares them with actual values using a scatter plot.

## Disclaimer
This project is for educational purposes and demonstrates basic machine learning concepts.

## Project Structure
Task6_House_Price_Prediction/
│
├── notebook.ipynb
├── README.md
└── dataset.csv



## Conclusion
The Linear Regression model successfully predicts house prices based on given features. Model performance can be improved further using advanced algorithms.
