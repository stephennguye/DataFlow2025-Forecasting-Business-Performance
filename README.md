# Forecasting Business Performance – DataFlow 2025 Contest

## Project Overview
This project was developed for the **DataFlow 2025 Data Analytics Contest**.  
Our team analyzed and forecasted the business performance of a U.S.-based fashion company for **2021–2022** and projected outcomes for **2023** to support:

- Inventory budgeting
- Supply chain optimization
- Effective stock management
- Strategic business planning

---

## Problem Statement
The task involved:
- Analyzing historical business data (2010–2022)
- Visualizing revenue and sales trends by year, month, and quarter
- Identifying economic, seasonal, and market factors affecting performance
- Building predictive models to forecast next year's revenue

### Evaluation Metrics
- **R² (Coefficient of Determination)** – Model fit  
- **MAPE (Mean Absolute Percentage Error)** – Percentage error measure  
- **RMSE (Root Mean Squared Error)** – Error magnitude  

---

## Methodology
### Data Analysis
- Trend visualization of revenue and sales volume
- Regional, product line, and segment analysis
- Seasonality detection and sales event analysis (e.g., summer promotions, back-to-school)

### Forecasting Models
1. **ARIMA / SARIMA** – Classical time series forecasting  
2. **RNN** – Recurrent Neural Network  
3. **LSTM** – Long Short-Term Memory Network  
4. **XGBoost** – Gradient boosting for time-series regression  

---

## Results & Insights
| Model     | R²     | MAPE     | RMSE   |
|-----------|--------|---------|--------|
| ARIMA     | 0.1071 | 163.61% | 0.7    |
| RNN       | 0.4787 | 21.20%  | 0.1236 |
| LSTM      | 0.5018 | 21.92%  | 0.1208 |
| XGBoost   | 0.9268 | 14.19%  | 0.1048 |

- **XGBoost** achieved the best performance due to its ability to model non-linear patterns.
- Revenue showed strong **seasonality** and **regional patterns**, with certain states and brands consistently outperforming others.
- 2023 revenue was forecasted to **continue a slight decline**, following previous years' trend.

---

## Strategic Recommendations
- Focus investments on high-performing regions (Texas, Florida, California, Washington).
- Continue strengthening top-performing brands (Maximus, Natura, Aliqui).
- Expand digital sales channels and marketing campaigns.
- Develop contingency plans for external factors (economic shifts, pandemics).

---

## Tools & Libraries
- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, XGBoost, TensorFlow/Keras

---

## Team
**Team No Name - USTH**  
- Phạm Duy Anh   
- Lê Quốc Anh  
- Nguyễn Thái Nhất Anh  
- Nguyễn Lâm Tùng  

---
