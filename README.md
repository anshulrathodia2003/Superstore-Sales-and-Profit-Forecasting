# Superstore Sales and Profit Forecasting

This project leverages **time-series analysis** to provide accurate, data-driven forecasts for a superstore's sales and profit. The main objective was to predict **monthly, category-wise sales** and **overall profit** for a two-year period (2018–2019) to support strategic decision-making in **inventory**, **marketing**, and **finance**.

---

## Methodology and Model

The core of this solution is the **Seasonal AutoRegressive Integrated Moving Average (SARIMA)** model, chosen because the historical data exhibited clear **trend** and **seasonal components**.

### Key Steps

1. **Data Preparation:**  
   Used four years of historical data (January 2014 – December 2017) with a monthly frequency.

2. **Stationarity Check:**  
   Conducted time-series analysis to confirm **stationarity** and applied differencing where necessary to stabilize mean and variance.

3. **Parameter Optimization:**  
   Determined the non-seasonal ($p, d, q$) and seasonal ($P, D, Q$) orders by analyzing **ACF** and **PACF** plots.

4. **Seasonal Period:**  
   Set the seasonal component ($s$) to 12 to capture the **annual cycle** inherent in the monthly sales and profit data.

---

## Business Impact and Visualization

The project results were deployed through a **dynamic business intelligence platform** to ensure easy access and interpretation for stakeholders.

### Power BI Dashboard

- Created an **interactive Power BI dashboard** to visualize both 4 years of historical data and 2 years of forecasted values.  
- Enabled stakeholders to efficiently monitor **expected growth trends**, seasonal **peaks**, and **troughs**.

### Key Recommendations

1. **Inventory Management:** Align stock levels with forecasted sales peaks to prevent **stockouts** and **overstocking**.  
2. **Financial Planning:** Utilize forecasted profit data for **accurate budgeting** and **efficient resource allocation**.  
3. **Marketing Strategy:** Schedule increased marketing efforts during predicted **peak sales periods** to maximize ROI.

---

## Technologies Used

- **Modeling:** SARIMA (Python)  
- **Data Visualization:** Power BI  
- **Data:** Historical Superstore Sales and Profit Data (2014–2017)
