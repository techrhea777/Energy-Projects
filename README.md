# Energy-Projects

Energy Consumption Forecasting for Westminster Domestic Sector

Project Overview

This project analyzes and forecasts energy consumption trends for the Westminster Domestic Sector using statistical and time-series techniques. By leveraging the LEGGI Dataset, the project provides actionable insights into historical energy usage patterns and future consumption forecasts, which can support strategic energy planning and decision-making.

Project Objectives
Analyze Borough-Level Energy Trends:

Explore how energy consumption varies across sectors and fuel types in Westminster and other boroughs.
Visualize energy usage patterns over time to identify key trends.
Perform Autocorrelation Analysis:

Examine the relationship between current and past energy consumption values to identify trends, seasonality, and lagged dependencies.
Forecast Energy Demand:

Build predictive models using OLS regression and ARIMA to forecast future energy consumption in Westminster's Domestic Sector.
Provide Data-Driven Insights:

Highlight key drivers of energy consumption and predict trends for the next 5 years.
Dataset Used
The project utilizes the London Energy and Greenhouse Gas Inventory (LEGGI) Dataset, which includes:

Columns:
Area: Borough name (e.g., Westminster, Camden).
LEGGI_Year: Year of energy consumption data.
Sector: Energy usage sector (e.g., Domestic, Industrial and Commercial, Transport).
Fuel: Type of fuel used (e.g., Gas, Electricity, Oil).
kWh: Total energy consumption in kilowatt-hours.
Methodology
The project is divided into three main steps:

1. Exploratory Data Analysis (EDA)
Purpose:
Understand historical trends in energy consumption.
Identify boroughs, sectors, and fuel types with the highest energy usage.
Visualizations:
Heatmaps to compare energy usage by sector and area.
Line plots showing trends in energy consumption over time.

2. Autocorrelation Analysis
Purpose:
Detect relationships between energy consumption values at different time lags (e.g., whether the current year’s usage depends on the previous year).
Method:
Use the autocorrelation function (ACF) to identify significant lags and seasonal patterns in the Westminster Domestic sector.

3. Energy Demand Forecasting
OLS Regression:
Quantify the impact of variables like Sector, Fuel, and Year on energy consumption.
Identify key drivers of energy demand.
ARIMA Time-Series Forecasting:
Build a predictive model to forecast Westminster Domestic energy consumption for the next 5 years.

Key Features
Data Analysis:
Aggregates and visualizes energy consumption trends by borough, sector, and fuel type.
Statistical Insights:
Performs autocorrelation to identify trends and dependencies.
Uses OLS regression to evaluate the contribution of different variables.
Predictive Modeling:
Builds time-series models to forecast future energy demand.
Provides actionable insights for energy policy and planning.

Results
Borough-Level Energy Insights:

Westminster has higher energy consumption in the Domestic Sector compared to other boroughs.
Gas is the dominant fuel type, showing a steady decline in usage over recent years.
Autocorrelation Analysis:

Significant autocorrelation at lag 1 indicates that the previous year's energy consumption strongly influences the current year's usage.
Insights suggest the inclusion of lagged variables in forecasting models.
Forecasting:

Forecasts predict a gradual decline in Domestic energy consumption for Westminster over the next 5 years.
This trend aligns with a shift toward energy efficiency and renewable sources.

Visualizations
Energy Consumption Heatmap:
Highlights energy usage by borough and sector.

Autocorrelation Plot:
Displays significant lag relationships in energy consumption data.

Forecasting Plot:
Compares actual and predicted energy consumption over time.
