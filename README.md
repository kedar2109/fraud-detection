# Credit Card Fraud Detection System 💳🕵️

## Project Overview:
This project implements a machine learning pipeline to detect fraudulent transactions using transaction data. It includes data preprocessing, feature engineering, and preparation for model training using scikit-learn's machine learning capabilities.

## Key Features:
Data Preprocessing: Handles datetime conversion and feature engineering

Feature Engineering: Creates time-based and geographical features

Geospatial Analysis: Calculates distance between locations using Haversine formula

Machine Learning Pipeline: Prepares data for classification with RandomForest

## Project Structure:
``` bash
fraud-detection/
├── main.ipynb                      # Main Jupyter notebook with implementation
├── fraudTrain.csv                  # Training dataset
├── fraudTest.csv                   # Testing dataset
├── test_data_with_predictions.csv  # Test data with predictions
├── fraud_detection_model.pkl       # Pickle file
├── requirements.txt                # Project reqirements
└── README.md                       # Project documentation
 ```
## Usage:

Clone repository:
``` bash
git clone https://github.com/kedar2109/fraud-detection

```

Install dependencies: 
``` bash
pip install -r requirements.txt
```
Run Jupyter notebook:
``` bash
 jupyter notebook main.ipynb
 ```
 
 ## Dataset Source:
This is a simulated credit card transaction dataset containing legitimate and fraud transactions from the
 duration 1st Jan 2019 - 31st Dec 2020. It covers credit cards of 1000 customers doing transactions with a
 pool of 800 merchants.