# Demand-Forecasting-and-Inventory-Optimization
**E-commerce Demand Forecasting & Inventory Optimization**
This project analyzes historical sales data from a health and nutrition e-commerce platform to:
Forecast demand using Prophet and ARIMA.
Optimize inventory levels to reduce stockouts and overstocking.
Provide actionable insights through Power BI dashboards.

**📊 Project Overview**
Small to medium e-commerce businesses often struggle with inventory management due to fluctuating demand.
Using historical sales data, this project builds forecasting models and inventory optimization strategies to:

Reduce stockouts

Avoid overstocking

Improve profitability

**📌 Key Objectives**
Simulate or use real e-commerce sales data for multiple SKUs.
Analyze trends, seasonality, and promotions using EDA.
Build Prophet and ARIMA forecasting models.
Calculate Safety Stock & Reorder Point.
Simulate stock scenarios for validation.
Create interactive Power BI dashboards.
Modularize code for reuse.

**🛠 Tools & Libraries**
Python: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, prophet
Forecasting Models: Prophet, ARIMA
Optimization: NumPy, SciPy
Dashboard: Power BI
Development Environment: Google Colab, Jupyter Notebook

**📈 Analysis Highlights**
Data Preparation – Cleaned and structured dataset with correct date formats.
EDA – Trends, seasonality (monthly & weekly), category/platform analysis.
Top Products & Categories – Identified revenue & volume leaders.
Discount Impact – Relationship between discount rates and sales performance.
Returns Analysis – Calculated return rates by product & category.

Forecasting:
Prophet – Trend, weekly & yearly seasonality detection.
ARIMA – Statistical time-series modeling.

Inventory Optimization – Safety Stock: 55.25 units, Reorder Point: 1,116.32 units.
Scenario Simulation – Validated inventory strategy under real demand patterns.
Power BI Dashboard – KPIs, trends, category/platform performance, geo maps.

**⚙️ Assumptions & Limitations**
Lead time fixed at 7 days.
Service level target 95%.
Historical patterns assumed to continue.
External factors (promotions, holidays, competitor pricing) not included.
