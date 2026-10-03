# Linear Regression from Scratch

A simple implementation of Linear Regression from scratch using Python and NumPy.

## About the Project

This project implements a Linear Regression model without using
machine-learning libraries such as Scikit-learn for the actual training.

The model predicts salary based on years of experience using the Salary Data
dataset.

## What I Implemented

- Linear Regression using the equation y = wx + b
- Random initialization of weight and bias
- Prediction function
- Mean Squared Error loss
- Gradient calculation
- Gradient Descent
- Early stopping based on convergence
- Loss tracking and visualization
- Prediction visualization

## How the Model Learns

The model starts with random values for weight and bias.

During training, it:

1. Makes predictions using y = wx + b
2. Calculates the prediction errors
3. Calculates the loss
4. Calculates gradients
5. Updates the weight and bias
6. Repeats the process until convergence

## Dataset

The dataset contains information about:

- Years of Experience
- Salary

The model uses Years of Experience as the input feature and Salary as the
target variable.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Structure

```text
Linear-Regression/
├── linear_regression.ipynb
├── Salary_Data.csv
└── README.md
