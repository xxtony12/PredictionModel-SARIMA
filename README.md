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
• RMSE: 16,674
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

