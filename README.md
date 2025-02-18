House Price Prediction Using Linear Regression
This repository contains a simple implementation of Linear Regression for predicting house prices based on the size of the house. The model uses training data that includes the house size (in square feet) and the corresponding price (in dollars). The objective is to predict the price of a house given its size.

Overview
The dataset consists of house sizes and corresponding prices.

The linear regression model uses the formula:

𝑦
=
𝑤
⋅
𝑥
+
𝑏
y=w⋅x+b
where:

y is the predicted price,
x is the size of the house,
w is the weight (slope), and
b is the bias (intercept).
The code visualizes both the actual data and the predicted values to assess the model's performance.

Key Features
Data Preprocessing: Simple dataset initialization using NumPy arrays.
Model Prediction: The model computes predictions based on the given linear equation.
Visualization: Plots the actual data and model predictions using Matplotlib.
Steps Involved
Data Visualization: Scatter plot to visualize the training data.
Model Prediction: Implementing linear regression to predict house prices.
Results Visualization: Plotting the predicted values against the actual values.
