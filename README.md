# Blinkit Price Prediction

## Overview
This project predicts product prices for Blinkit items using Machine Learning and XGBoost algorithms. The model analyzes product attributes and generates accurate price predictions.

## Problem Statement
Predict the selling price of products based on various features such as product category, weight, visibility, outlet type, and other relevant attributes.

## Features
- Data preprocessing and cleaning
- Feature engineering
- XGBoost Regression Model
- XGBoost Classification Model
- Interactive web interface
- Real-time price prediction

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Flask
- HTML/CSS
- Joblib

## Project Structure

Blinkit_price_prediction/
│
├── app.py
├── index.html
├── requirements.txt
├── xgb_classifier_model.joblib
├── xgb_regressor_model.joblib
└── Big Data Project Code.ipynb

## Installation

1. Clone the repository

git clone https://github.com/nehatyagi17/Blinkit_price_prediction.git

2. Install dependencies

pip install -r requirements.txt

3. Run the application

python app.py

## Model Performance

| Model | Purpose |
|---------|---------|
| XGBoost Regressor | Price Prediction |
| XGBoost Classifier | Product Classification |

## Future Enhancements
- Deploy on Render/Streamlit
- Improve prediction accuracy
- Add visualization dashboard
- Enable batch predictions

## Author
Neha Tyagi
