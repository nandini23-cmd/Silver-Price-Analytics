# Silver Price Analytics

End-to-end silver commodity price analysis project covering 2000–2025.

## Project Overview
This project was completed as part of a 14-day BFSI Data Analytics Internship at Zetheta Algorithms Pvt. Ltd. It covers the full data science pipeline from raw data ingestion through machine learning modelling, ensemble forecasting, and Power BI dashboard development.

## Repository Structure
- /data — Raw CSV datasets (5 files)
- /notebooks — Google Colab notebooks (Days 1–14)
- /models — Saved model files
- /dashboards — Power BI dashboard (.pbix)
- /reports — Final report, case studies, presentation

## Datasets
- silver_daily_ohlcv_2000_2025.csv (6,783 rows)
- silver_futures_contracts.csv
- silver_macroeconomic_indicators.csv
- silver_sentiment_weekly.csv
- silver_supply_demand.csv

## Models Built
- ARIMA (5,1,0) — MAE $7.79, MAPE 28.17%
- SMA Baseline — MAE $8.00, MAPE 28.93%
- LSTM, XGBoost, Random Forest, Linear Regression

## Tech Stack
- Python: pandas, numpy, statsmodels, scikit-learn
- Power BI Desktop: 17+ DAX measures, 4 dashboard pages
- Google Colab

## Setup
1. Clone the repository
2. Install dependencies: pip install -r requirements.txt
3. Run notebooks in /notebooks folder in order

## Author
Nandini | MBA Business Analytics | Parul University
BFSI Data Analytics Internship 2025-26 | Zetheta Algorithms Pvt. Ltd.
