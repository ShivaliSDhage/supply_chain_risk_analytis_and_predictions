# AI-Driven Supply Chain Risk Prediction

## Project Overview

This research project investigates the effectiveness of machine learning models in predicting supply chain disruptions caused by natural disasters. By comparing traditional forecasting methods with advanced ML techniques, we aim to enhance supply chain risk management strategies and improve resilience against environmental uncertainties.

## Key Features

- Data integration from multiple sources (supply chain operations, natural disasters, weather patterns)
- Comprehensive data preprocessing and feature engineering
- Implementation of multiple ML models (Random Forest, XGBoost, SVM, Logistic Regression)
- Comparative analysis with traditional forecasting methods (ARIMA)
- Visualization of model performance and feature importance
- Real-world case studies validation

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Statsmodels, pmdarima

## Key Findings

- XGBoost outperformed other models with 79.1% accuracy in predicting supply chain disruptions
- ML models showed a 16.9% improvement over traditional forecasting methods
- Short-term predictions (1-7 days) achieved the highest accuracy at 85.3%
- Key predictive factors include historical disaster frequency, extreme weather conditions, and supply chain complexity

## Installation and Usage

1. Clone the repository:
   https://github.com/ShivaliSDhage/supply_chain_risk_analytis_and_predictions.git
2. Install required packages: pip install -r requirements.txt
3. Run the main script: python supply_chain_analytics_final.py

## Data Sources

- Supply Chain Operations Data (Brunel University London Research Dataset) : https://brunel.figshare.com/articles/dataset/Supply_Chain_Logistics_Problem_Dataset/7558679?file=20162015
- EM-DAT (Emergency Events Database) maintained by the Centre for Research on the Epidemiology of Disasters (CRED)
- NOAA Global Historical Climatology Network Daily (GHCN-Daily)

## Future Work

- Incorporate real-time data streams for more dynamic predictions
- Explore transfer learning techniques for improved generalization
- Develop a user-friendly interface for practical implementation in industry settings

