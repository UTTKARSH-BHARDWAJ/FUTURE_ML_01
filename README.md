# Sales Forecasting and Visualization using Prophet & Power BI

## Overview

This project focuses on analyzing historical sales data and generating time series forecasts using the Facebook Prophet model. The forecasted results are visualized using Power BI to deliver clear, actionable business insights.

The objective is to understand sales trends, seasonality, and future demand to support data-driven decision-making.

---

## Dataset

- **Source:** Walmart US Sales Dataset  
- **Format:** csv (.csv)  
- **Granularity:** Daily sales data  

### Key Fields
- Invoice Date  
- Category  
- Region / Store  
- Total Sales  

Raw data is stored separately from processed data to ensure reproducibility.


---

## Methodology

### 1. Data Preprocessing
- Converted date columns to datetime format  
- Aggregated sales at the daily level  
- Handled missing values and inconsistencies  

### 2. Time Series Forecasting
- Used Facebook Prophet for forecasting  
- Modeled trend and seasonality  
- Generated future predictions using `make_future_dataframe`  
- Evaluated the model using MAE and MSE  

### 3. Visualization
- Exported forecast results to CSV  
- Built an interactive Power BI dashboard  

---

## Power BI Dashboard Features

- Actual vs forecasted sales trends  
- Monthly and yearly sales comparisons  
- Filters by category, store, and region  
- Identification of top-selling categories and low-sales periods  
- Insight cards for business decision-making  

---

## Tools & Technologies

- Python  
- Pandas, NumPy  
- Prophet  
- Scikit-learn  
- Power BI  
- Jupyter Notebook  


---

## Results & Insights

- Identified clear sales trends and seasonality patterns  
- Generated short-term forecasts to support planning  
- Daily forecasts provide granular insights  
- Forecast comparison highlights gaps between expected and actual performance  

---

## Conclusion

This project demonstrates an end-to-end time series forecasting workflow, including data preprocessing, modeling with Prophet, and visualization using Power BI. The analysis provides actionable insights into sales trends and future demand.

The approach can be further enhanced by incorporating holidays, promotions, or external regressors.

---

## Author

Uttkarsh Bhardwaj




