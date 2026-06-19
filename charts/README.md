# House Price Prediction

## Project Overview
This project predicts house prices using Machine Learning techniques. The dataset was preprocessed, categorical variables were encoded using One-Hot Encoding, and predictive models were trained and evaluated.

## Dataset
- Housing.csv

## Tasks Performed
1. Data Cleaning and Preprocessing
2. Feature Encoding
3. Exploratory Data Analysis (EDA)
4. Model Training using Linear Regression
5. Model Evaluation and Comparison with Random Forest Regressor

## Results
- Linear Regression
  - MAE: 970,043
  - RMSE: 1,324,507
  - R² Score: 0.653

- Random Forest Regressor
  - MAE: 1,016,000
  - RMSE: 1,390,000
  - R² Score: 0.613

## Repository Structure

HousePricePrediction_[YourName]/
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
└── charts/
    ├── histogram_price.png
    ├── area_vs_price.png
    └── correlation_heatmap.png

## Conclusion
Linear Regression outperformed Random Forest on this dataset and was able to explain approximately 65% of the variation in house prices.
