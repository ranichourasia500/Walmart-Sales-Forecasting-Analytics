# 🛒 Walmart Sales Analysis & Forecasting

## 📌 Project Overview

This project focuses on analyzing and predicting the *weekly sales performance* of a retail chain across multiple stores. Using historical data, the analysis explores how *macroeconomic and environmental factors*—such as unemployment, CPI, fuel prices, and temperature—impact sales and customer behavior.

The project is divided into two main phases:

* 🔍 *Exploratory Data Analysis (EDA) & Statistical Testing*
* 📈 *Predictive Modeling (Time-Series Forecasting)*

---

## 🎯 Key Objectives

* Identify the relationship between sales and external factors (CPI, unemployment, weather)
* Analyze performance differences across stores
* Detect seasonal patterns and holiday sales spikes
* Perform data cleaning, outlier detection, and missing value handling
* Build forecasting models to predict sales for the next 12 weeks

---

## 📊 Dataset Description

* *Source:* Walmart Dataset (Kaggle)
* *Size:* 6,435 rows × 8 columns

### Features:

* Store ID
* Date
* Weekly Sales
* Holiday Flag (1 = Holiday)
* Temperature (°F)
* Fuel Price
* CPI
* Unemployment Rate

---

## 🔍 Key Insights

* 🏆 *Top Performer:* Store 20 (~$2.07M avg weekly sales)

* 📉 *Lowest Performer:* Store 33 (~$0.26M avg weekly sales)

* 📊 *Performance Gap:* ~87.67% difference between top and bottom stores

* 📉 *Macroeconomic Impact:*

  * Unemployment shows a *significant negative impact* on sales

* 🎯 *Seasonality:*

  * Sales spike during holidays
  * Monthly variation is *not statistically significant* (ANOVA p = 0.33)

* 🌡️ *Weather Effect:*

  * Sales increase with temperature initially
  * Decline observed during extreme heat (non-linear relationship)

---

## 📈 Modeling Approach

* Time-Series Forecasting using *ARIMA*
* Predicted sales for the *next 12 weeks*
* Used insights for demand planning and optimization

---

## 🧠 Conclusions

* Holiday periods are the *primary drivers of sales spikes*
* Economic factors like unemployment and CPI directly influence sales
* Large performance variation indicates *store-specific operational differences*

---

## 💡 Strategic Recommendations

* 🎯 Focus promotions on stores sensitive to unemployment (e.g., Stores 29, 37, 42, 43)
* 📦 Use forecasting models for *inventory optimization*
* 📢 Allocate marketing budget to *high-performing stores* (Store 20, Store 4)
* 🔍 Analyze top-performing stores to replicate best practices in low-performing stores

---

## 🛠️ Tools & Technologies

* Python (Pandas, NumPy)
* Data Visualization (Matplotlib, Seaborn)
* Statistical Analysis (ANOVA)
* Time-Series Forecasting (ARIMA)

---

## 🚀 Project Outcome

This project demonstrates the ability to:

* Perform end-to-end *data analysis*
* Apply *statistical testing*
* Build *predictive models*
* Generate *business insights & recommendations*

---

⭐ Turning data into actionable insights for smarter business decisions.
