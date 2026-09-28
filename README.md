# Retail Demand Forecasting & Sales Analytics

An end-to-end retail analytics project focused on understanding sales performance, customer behaviour, promotional patterns, store-level performance, and demand forecasting using Python and Power BI.

## Project Overview

This project uses historical retail sales data to identify key business patterns and build a demand forecasting workflow.

The analysis covers:

- Data cleaning and preparation
- Exploratory Data Analysis (EDA)
- Sales and customer analysis
- Store-level performance analysis
- Promotion analysis
- Seasonality analysis
- Competition analysis
- Demand forecasting
- Forecast model comparison
- Interactive Power BI dashboard

## Business Objectives

- How do sales vary across stores?
- Which store types generate higher average sales?
- How do promotional days relate to sales?
- What seasonal patterns exist in retail sales?
- How does customer volume relate to sales?
- Which stores show higher average performance?
- Can historical sales be used to forecast future demand?

## Dataset

The project uses the **Rossmann Store Sales** dataset.

The dataset contains historical information about:

- Store
- Date
- Sales
- Customers
- Promotions
- Holidays
- Store Type
- Assortment
- Competition Distance

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Power BI
- Jupyter Notebook

## Project Workflow

1. Data Preparation
2. Exploratory Data Analysis
3. Business Analysis
4. Demand Forecasting
5. Model Evaluation
6. Power BI Dashboard

## Demand Forecasting

Forecasting was performed for **Store 817** using two approaches:

1. Naive Forecast
2. Holt-Winters Exponential Smoothing

A chronological train-test split was used to avoid data leakage.

## Model Evaluation

| Model | MAE |
|---|---:|
| Naive Forecast | 3836.55 |
| Holt-Winters | 5082.62 |

For the selected Store 817 test period, the Naive Forecast produced a lower MAE.

## Key Insights

- Promotional days showed higher average sales than non-promotional days.
- Customer count showed a strong positive association with sales.
- Sales varied significantly across stores.
- Store Type B recorded the highest average sales.
- December showed recurring seasonal peaks.
- Store-level performance differed considerably.
- Store 817 showed high average sales performance.
- The Naive Forecast produced lower test MAE than Holt-Winters for Store 817.

## Power BI Dashboard

The dashboard includes:

- Total Sales
- Total Customers
- Total Stores
- Average Sales
- Sales Trend
- Sales by Store Type
- Sales by Promotion
- Sales by Day of Week
- Top Performing Stores
- Sales by Competition Range
- Forecast Model Comparison
- Actual vs Forecast

## Forecasting Approach

Historical Sales  
→ Time-Based Train/Test Split  
→ Naive Forecast  
→ Holt-Winters  
→ MAE Evaluation  
→ Business Interpretation

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Business Analytics
- Time Series Forecasting
- Model Evaluation
- Data Visualization
- Power BI Dashboard Development
- Business Insight Generation

## Future Improvements

- Test additional forecasting approaches
- Build forecasts for multiple stores
- Add automated model selection
- Integrate SQL/database-based analysis
- Develop automated forecast refresh workflows