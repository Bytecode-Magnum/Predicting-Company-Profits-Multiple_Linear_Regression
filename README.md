## Project Title:
 Predicting Profits using Multiple Linear Regression

##Project Description
This project focuses on predicting profits for a company based on various factors using a multiple linear regression model. By analyzing the provided dataset containing information on R&D Spend, Administration, Marketing Spend, and State, we aim to understand how these variables affect the company's profitability. This repository showcases the entire process, from data exploration and analysis to building and evaluating the predictive model.

## Dataset Overview
The dataset consists of samples with features like R&D Spend, Administration, Marketing Spend, and State. Each sample also includes the corresponding Profit value. The goal is to create a model that can accurately predict the Profit based on these features.

[DataSet](https://github.com/Bytecode-Magnum/Predicting-Company-Profits-Multiple_Linear_Regression/blob/main/profit_predication_data.csv)

## Key Steps
### Data Exploration: 
The initial phase involved understanding the dataset's structure, checking for missing values, and gaining insights into the distribution of the variables. This step is crucial for identifying any data quality issues and getting a sense of the data's characteristics.

### Data Analysis:
 By visualizing the relationships between R&D Spend, Administration, Marketing Spend, State, and Profit, we gained insights into how these variables are correlated and how they contribute to the profitability of the company. This analysis helped in making informed decisions about feature selection.

### Feature Engineering: 
Given the categorical nature of the "State" variable, it was necessary to encode it properly to make it suitable for the regression model. This involved using techniques like one-hot encoding to convert categorical data into numerical form.

### Model Building: 
Utilizing the insights gained from the data analysis, we proceeded to build a multiple linear regression model. The model incorporated the selected features to predict Profit. Libraries such as scikit-learn were employed for this purpose.

### Model Evaluation: 
To assess the model's performance, we used metrics like Mean Squared Error (MSE) and R-squared. These metrics provide a quantitative measure of how well the model fits the data and its predictive capabilities.

[Model](https://github.com/Bytecode-Magnum/Predicting-Company-Profits-Multiple_Linear_Regression/blob/main/Profit_Prediction.ipynb)

