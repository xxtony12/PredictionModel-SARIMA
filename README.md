# How to Run the Project

1. Install dependencies:
pip install pandas numpy matplotlib scikit-learn statsmodels

2. Run script:
python sarima_forecasting_model.py

# Revenue Forecasting Using SARIMA Time-Series Modeling

## Project Overview
Developed a time-series forecasting model to predict daily revenue trends for a UK-based online wholesale retailer using transactional sales data.

The objective was to provide forward-looking financial insight to support inventory planning, supply chain decisions, and revenue forecasting.

## Business Problem
Wholesale retail operations require accurate demand forecasting to optimize inventory levels, staffing, and financial planning. Unreliable demand projections can lead to lost sales or excess inventory costs.

## Data Preparation
• Removed return transactions and pricing anomalies
• Engineered revenue feature (Quantity × Unit Price)
• Aggregated transactional data into daily revenue time series
• Implemented 80/20 temporal train-test split

## Modeling Approach
• Tested Prophet and ARIMA models
• Selected SARIMA to capture seasonality and cyclic demand patterns
• Tuned parameters using stationarity testing and differencing

## Model Evaluation

The model achieved a MAPE of 33%, indicating moderate forecasting accuracy for highly sparatic wholesale revenue patterns. Future improvements include outlier smoothing and external feature integration such as seasonality drivers and promotions.

<img width="727" height="453" alt="Screenshot 2026-02-09 at 4 31 36 PM" src="https://github.com/user-attachments/assets/aff40d0f-37f9-4f87-9985-b524fa9a0d6c" />

• RSME: 16,674
• MAPE: 33.49%
Outlier analysis revealed large sales spikes that influenced model variance and identified opportunities for future model refinement.

## Business Impact
The forecasting model enables:
• Improved financial planning
• Better inventory allocation
• Early identification of revenue fluctuations
• Data-driven strategic planning

## Tools Used
Python, Pandas, Statsmodels, Matplotlib, NumPy, Scikit-learn

