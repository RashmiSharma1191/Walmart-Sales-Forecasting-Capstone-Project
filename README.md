# 🏪 Walmart-Sales-Forecasting-Capstone-Project

## 📌 Problem Statement

A retail chain with multiple outlets across the country is facing challenges in managing inventory to effectively match demand and supply.
This project focuses on using data-driven techniques to predict future sales and assist Walmart in optimizing inventory and operational decisions.

## 🎯 Project Objective

The goal of this project is to forecast store sales for the next 12 weeks using machine learning techniques.
By analyzing time-based data, holiday effects, fuel prices, and the Consumer Price Index (CPI), this project aims to assess how temporal and external factors influence Walmart’s sales performance.

## 🧾 Data Description

The dataset includes historical weekly sales data from 45 Walmart stores, with features such as:
- Store locations
- Weekly sales data
- Special events and holidays
- CPI (Consumer Price Index)
- Fuel prices

This dataset helps uncover patterns, trends, and anomalies that affect sales, allowing Walmart to plan inventory more efficiently and reduce stockouts.

## ⚙️ Algorithm and Motivation

The project utilizes the SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous factors) model from the statsmodels library. SARIMAX was chosen because it is highly effective for retail sales forecasting, allowing the model to capture complex weekly seasonality and long-term trends while simultaneously integrating the influence of external economic variables (like Fuel Prices and CPI) and holiday events.

## 🧠 Assumptions

Accurate forecasting requires sufficient and relevant historical data.
Missing factors like demographics or local store conditions may reduce prediction accuracy.
The available dataset provides limited context for fully capturing real-world dynamics.

## 📊 Model Evaluation and Techniques

The project applies time-series forecasting models using historical sales data for each store.
Techniques include:
- Data preprocessing and feature engineering,
- Training models on store-level data,
- Evaluating results through visualization of training vs. test data and confidence intervals.

These techniques help capture seasonality, trends, and random variations influencing sales.

## 🏆 Key Insights & Business Impact

The predictive analysis generated these actionable insights for operational improvement:
- Peak Seasonality: Sales are highly concentrated in Weeks 47 and 51 (Thanksgiving and Christmas), necessitating maximum inventory and staffing during these periods.
- Store Performance: Store 20 and Store 4 show the highest average weekly sales, providing benchmarks for operational best practices to be replicated across the chain.
- Economic Sensitivity: A clear negative correlation was observed between Unemployment Rate and weekly sales, suggesting inventory should be managed conservatively in economically strained regions.
- Post-Holiday Drop: Sales drop significantly in January following the peak Q4 season. Action: Targeted clearance promotions are recommended in January to manage inventory backlog.
- Annual Trend: While overall sales might have peaked in 2010, the consistency of sales growth in 2012 (even without the best months) suggests underlying stability. Action: Focus should be on relative YoY growth in the first 10 months to gauge true performance.
  
## 🚀 Future Scope

Potential extensions include:

- Incorporating advanced Deep Learning models (e.g., LSTMs) for enhanced long-term prediction accuracy.
- Integrating external datasets such as local competitor data and regional promotional calendars for richer context.
- Deploying a dashboard or web app to visualize real-time sales forecasts for each store manager.

## 📊 Visualization

Visual analysis includes:
Graphs comparing training data, actual test data, and forecasts. Confidence intervals for visualizing model reliability and accuracy.
![Graph](https://github.com/RashmiSharma1191/Walmart-Sales-Forecasting-Capstone-Project/blob/main/SARIMA%20TRAINED%20GRAPH.png)

(Note: The visualization above shows the model's fit on historical data and the 12-week forecast with its 95% confidence bounds.)

## 🧾 References
- Kaggle Datasets
- YouTube Tutorials
- GitHub Repositories
- Medium Blogs & Data Science Articles

## 👩‍💻 Author
**Rashmi Sharma**  

📧 [Mail ID](mailto:rashusharma007@gmail.com)

🔗 [LinkedIn Profile](https://www.linkedin.com/in/rashmi-sharma-11nv91)


