# US Corn Balance Sheet Forecast (2025)

This project forecasts the 2025 US corn balance sheet using USDA data and machine learning models. Components like yield, imports, demand, ending stocks, and average farm price are predicted using historical trends and trained regressors.

---

## Project Overview

- Domain: US Agriculture / Commodity Markets  
- Goal: Forecast 2025 corn balance sheet attributes using machine learning  
- Data Source: USDA WASDE reports and internal historical estimates  
- Methods Used
  - Linear Regression
  - Random Forest
  - XGBoost
  - Feature selection, tuning, and evaluation

---

## Forecasted Variables

| Component             | Units                |
|-----------------------|----------------------|
| Yield                 | Bushels per acre     |
| Production            | Million bushels      |
| Imports               | Million bushels      |
| Total Demand          | Million bushels      |
| Ending Stocks         | Million bushels      |
| Average Farm Price    | US Dollars per bushel|

---

## Key Skills Demonstrated

- Data preparation and cleaning using `pandas`
- Feature engineering and exploratory analysis
- Regression modeling with `scikit-learn` and `xgboost`
- Forecasting with realistic economic assumptions
- Visualization with `matplotlib` and `seaborn`
- Performance evaluation using R² and RMSE

---

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/us-corn-balance-sheet-forecast.git
cd us-corn-balance-sheet-forecast
