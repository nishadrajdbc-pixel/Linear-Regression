🏠 House Price Prediction using Linear Regression

📌 Project Overview

This project implements Simple and Multiple Linear Regression to predict house prices using a housing dataset. The model learns the relationship between various housing features and the final sale price.

📊 Dataset

The dataset contains both numerical and categorical features such as:

Numerical Features: area, bedrooms, bathrooms, stories, parking

Binary Features (Yes/No): mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea

Categorical Feature: furnishingstatus

Target Variable: price

Categorical values were converted to numeric format using:

Binary Encoding (Yes → 1, No → 0)

One-Hot Encoding for multi-category features

🧠 Concepts Covered

Simple Linear Regression

Multiple Linear Regression

Data Preprocessing

Handling Categorical Variables

Train-Test Split

Model Evaluation (MAE, RMSE, R² Score)

Interpretation of Regression Coefficients

⚙️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

🚀 Model Workflow

Load and explore dataset

Convert categorical variables to numeric

Split data into training and testing sets

Train Linear Regression model

Evaluate performance using MAE, RMSE, and R²

Interpret feature coefficients

📈 Results

The Multiple Linear Regression model explains a significant portion of variance in house prices and demonstrates how different features (area, bathrooms, air conditioning, etc.) impact pricing.

📎 How to Run

Clone the repository

Install required libraries

Run the Python notebook/script

🎯 Key Learning

This project demonstrates how regression models can be used to understand feature impact and make price predictions in real-world dataset.
