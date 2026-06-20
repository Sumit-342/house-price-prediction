# House Price Prediction

## Overview

This project focuses on predicting house prices using Machine Learning techniques. The dataset was analyzed, cleaned, and preprocessed before training different regression models. The performance of the models was evaluated using standard regression metrics.

## Dataset

- Dataset: Housing.csv
- Total Records: 545
- Target Variable: "price"
- Features: Area, Bedrooms, Bathrooms, Stories, Parking, Air Conditioning, and other house-related attributes.

## Project Tasks

1. Data Loading & Exploration

- Loaded the dataset using Pandas.
- Examined the structure of the dataset.
- Identified target and feature columns.
- Checked for missing values.

2. Data Cleaning

- Verified missing values and duplicate records.
- Converted categorical variables into numerical format using One-Hot Encoding.
- Prepared the dataset for machine learning models.

3. Model Building

Two regression models were trained:

- Linear Regression
- Random Forest Regressor

4. Model Evaluation

## Metrics Used:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Results:

Model| R² Score
Linear Regression| 0.653
Random Forest Regressor| 0.612

Linear Regression performed slightly better on this dataset.

5. Visualization

The following visualizations were created:

- House Price Distribution Histogram
- Correlation Heatmap
- Actual vs Predicted Price Scatter Plot

## Technologies Used

- Python 3
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

HousePricePrediction_Sumit/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
├── charts/
│   ├── house_price_distribution.png
│   ├── correlation_heatmap.png
│   └── actual_vs_predicted_prices.png
├── requirements.txt
└── README.md

## Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing
- Feature encoding
- Machine Learning model training
- Model evaluation
- Data visualization
- End-to-end machine learning workflow

Author

Sumit Singh 
