# Used Cars Price Prediction

Developed a predictive pricing model to estimate the resale value of used cars, enabling better pricing strategies and market insights for buyers and sellers.

## Overview

This project focuses on building a machine learning model to predict the price of used cars in the Indian market. With the growing demand for pre-owned vehicles, accurately pricing them is essential for both buyers and sellers. Unlike new cars, where prices are standardised, used car prices vary based on multiple factors such as mileage, brand, year, fuel type, and transmission. The model helps businesses optimise pricing strategies, improve profitability, and enhance customer confidence.

## Objective

The goal is to develop a pricing model that accurately predicts the market value of used cars based on various attributes, helping businesses set competitive prices and maximise profits.

## Tools and Techniques

### Programming Language - Python 3.8

### Libraries
- Data Manipulation: Pandas, NumPy
- Data Visualisation: Matplotlib, Seaborn
- Modeling: Scikit-learn (Linear Regression, Decision Tree, Random Forest, Gradient Boosting)
- Evaluation Metrics: RMSE, MAE, R² Score

### Techniques
- Data Cleaning & Preprocessing
- Handling Missing Values & Outliers
- Feature Engineering & Selection
- Train-Test Splitting
- Hyperparameter Tuning (GridSearchCV)
- Model Performance Evaluation

## Dataset
The dataset contains key attributes influencing the resale price of used cars. By leveraging machine learning, this model aims to bring transparency and accuracy to used car pricing, benefiting both buyers and sellers in the market.

### Target Variable
- Price: The resale price of the used car (in INR 100,000)

### Vehicle Attributes
- Name: Car brand and model
- Year: Manufacturing year
- Kilometers Driven: Total distance traveled by the car
- Fuel Type: Petrol, Diesel, Electric, CNG, LPG
- Transmission: Automatic or Manual
- Owner Type: First, second, or third owner
- Mileage: Mileage provided by the car (KMPL or KM/KG)
- Engine: Engine displacement (CC)
- Power: Maximum engine power (BHP)
- Seats: Number of seats in the car

### Market Factors
- Location: City where the car is available for sale
- New Price: Price of a new car of the same model (INR 100,000)
