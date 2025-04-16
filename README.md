# Food price Analysis in Nigeria

## 📌 Project Overview
-----
This project analyzes food prices across various Nigerian regions and markets using Excel, MySQL and Power BI. The goal is to identify price trends, regional disparities, and data quality issues in food commodities.


![image alt](https://github.com/Abolanle890/Food_price/blob/a7493d8ebd6a2a6d2715a78332b51e8ce9c70424/Bar%20Chat.png)
### Commodity Price Analysis
The bar chart above visualizes the total price distribution across different food commodities. It highlights the top five commodities by total price recorded: Groundnuts (shelled) and Local Rice are the most expensive overall, each surpassing ₦25 million.Cowpeas (white) and Cowpeas (brown) follow closely behind.Yam rounds out the top five.This visualization helps identify which food items contribute most significantly to total food expenditure over the period analyzed.

![image alt](https://github.com/Abolanle890/Food_price/blob/1ee30344881a622aba9df798e49b01264e68b31d/Horizontal%20Bar%20Chat%20(2).png)
### Sum of Price Admin_1 (State)
This bar chart summarizes total price values at the state level (admin_1). Borno records the highest price sum, with Yobe and Kaduna following. This visualization gives a macro-level overview of which states drive the most value in the dataset.

![image alt](https://github.com/Abolanle890/Food_price/blob/7ae82aabe5a000573ee73e118d51ec1fdb224c32/Horizontal%20Bar%20chat.png)
### Sum of Price by admin_2 (Local Government Areas)
This horizontal bar chart breaks down the total price values by local government areas (admin_2). Maiduguri stands out as the highest contributor, followed by Gwandu and Ibadan North, indicating regional concentration of price activity at the LGA level.


##  Dataset Information
The dataset used in this project was sourced from the Humanitarian Data Exchange (HDX), provided by the World Food Programme (WFP).
Dataset Title: WFP Food Prices for Nigeria
Provider: World Food Programme (WFP) [WFP Food Prices for Nigeria](https://data.humdata.org/dataset/wfp-food-prices-for-nigeria) dataset on the [Humanitarian Data Exchange (HDX)](https://data.humdata.org/), provided by the World Food Programme (WFP).
License: Open data, available under the HDX Terms of Use
Data Frequency: Monthly
Coverage: Includes market-level food price data across Nigeria, with details on:
Date
Location (Admin 1 & 2, Market)
Commodity & Category
Unit of measurement
Local price, currency, and USD price
Price type and price flag

## 📁 Dataset Fields
- Date
- Admin_1 (State)
- Admin_2 (Local Government Area)
- Market
- Category
- Commodity
- Commodity_ID
- Unit
- Price_Type
- Price_Flag
- Currency
- Price
- USD_Price

## 🧠 Key Insights
- Monthly price trend of key commodities
- Top 5 most expensive commodities
- Regions with highest food prices
- Suspicious/flagged price entries

## 🔍 Expository Data Analysis
After cleaning and analyzing the WFP food price dataset for Nigeria, several key patterns and insights emerged:
1) Price Trends Over Time
- Most staple food commodities (e.g., Yam, rice, beans) showed a steady increase in USD prices
- The rise corresponds with inflation and currency devaluation in Nigeria, highlighting external economic pressures.
2) Regional Price Disparities
- Northern states like Borno and Yobe often had lower prices, especially for grains.
- Southern urban centers (e.g., Lagos, Port Harcourt) recorded consistently higher prices, likely due to increased demand and supply chain costs.
3)  Market-Level Insights
- Some markets consistently reported higher or lower prices for the same commodities, suggesting local supply dynamics or possible data anomalies.
- Flagged prices or zero USD prices appeared in multiple records, highlighting the need for careful data validation.
4)  Commodity Focus
- Rice and Yam were the most frequently tracked commodities.

## Recommendations
Based on the analysis, here are some actionable insights:
- Support Targeted Subsidies
- Government and NGOs can use price trend data to target interventions in regions with consistently high food prices.
- Monitor Supply Chain Inefficiencies
- Markets with unusual price spikes could indicate logistical or supply bottlenecks that require deeper investigation.
- Standardize Data Collection
- Track Inflation Adjusted Trends

## 📊 Tools Used
- MySQL
- Power BI
- Excel

## 📈 Dashboard
[Link to your dashboard]


