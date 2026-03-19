Walmart Sales Analysis & Forecasting Capstone Project
Project Overview
This project, developed by Rani Chourasia , focuses on analyzing and predicting the weekly sales performance of a retail chain with multiple outlets across the country. By leveraging historical data, the study explores how socio-economic and environmental factors—such as Unemployment Rates, Consumer Price Index (CPI), Fuel Prices, and Temperature—impact consumer behavior and store performance.
The project is structured into two primary phases:
1.	Exploratory Data Analysis (EDA) & Statistical Testing: Identifying trends, seasonality, and the impact of macroeconomic variables.
2.	Predictive Modeling: Developing time-series models to forecast future sales for inventory and resource optimization.
________________________________________
Key Objectives
•	Identify Drivers: Understand the relationship between sales and external factors like CPI, unemployment, and weather.
•	Performance Benchmarking: Determine top and bottom-performing stores and analyze the performance gap.
•	Seasonality Analysis: Detect seasonal patterns and holiday spikes in sales.
•	Data Reliability: Conduct outlier analysis and handle missing values to ensure high-quality insights.
•	Forecasting: Develop predictive models to forecast sales for each store for the next 12 weeks.
________________________________________
Dataset Description
The analysis utilizes Walmart's historical sales records (sourced from Kaggle).
•	Size: 6,435 rows and 8 columns.
•	Features: Store ID, Date, Weekly Sales, Holiday Flag ($1=$ Holiday), Temperature ($^\circ$F), Fuel Price, CPI, and Unemployment Rate.
________________________________________
Key Insights
•	Performance Disparity: Store 20 was the best performer (~$2.07M average weekly sales), while Store 33 was the weakest (~$0.26M).
•	The Gap: There is a significant 87.67% percentage difference between the highest and lowest performing stores.
•	Macroeconomic Impact: Unemployment has a statistically significant negative impact on sales.
•	Seasonality: While sales show sharp peaks during holidays, ANOVA testing ($p = 0.33$) indicates that the month itself does not have a statistically significant effect on average sales.
•	Weather Effects: Sales vs. Temperature shows a non-linear relationship; sales initially increase with temperature but begin to decline during extreme heat.
________________________________________
Conclusions
•	Seasonality Drives Peaks: Although monthly averages are stable, specific holiday periods and promotions are the primary drivers of sales spikes.
•	Economic Sensitivity: Customer spending is directly reduced by rising unemployment and inflation (CPI), though this effect is not uniform across all store locations.
•	Operational Variance: The massive 87% gap between top and bottom stores suggests that location-specific factors and management practices strongly influence outcomes.
________________________________________
Strategic Recommendations
•	Targeted Support: Walmart should focus on aggressive promotions or discounts in stores most sensitive to unemployment (e.g., Stores 29, 37, 42, and 43) during economic downturns.
•	Inventory Planning: Use the 12-week ARIMA forecasts to align inventory levels with predicted demand fluctuations, preventing overstocking or stockouts.
•	Optimized Marketing: Shift marketing resources toward high-performing "benchmark" stores (like Store 20 and 4) to maximize ROI during seasonal peaks.
•	Store-Specific Strategy: Investigate the management and location advantages of top-performing stores to apply those "best practices" to underperforming outlets like Store 33.
________________________________________
Technologies Used
•	Python: Core analysis and automation.
•	Pandas & NumPy: Data cleaning and feature engineering.
•	Matplotlib & Seaborn: Visualization of trends and correlation matrices.
•	Statsmodels: ANOVA testing, OLS regression, and ARIMA forecasting.
•	Google Colab: Development environment.

# Walmart-Sales-Forecasting-Analytics
