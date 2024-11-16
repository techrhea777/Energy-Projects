Borough-Level Energy Demand Forecasting and Trend Analysis
Overview
This project explores and forecasts energy consumption trends across boroughs in London using the LEGGI dataset. The analysis leverages statistical techniques like OLS regression, autocorrelation analysis, and time-series forecasting (ARIMA) to uncover actionable insights and predict future energy demand.

Objectives
Analyze Historical Trends:
Explore energy consumption patterns by sector, fuel type, and borough.
Identify Key Drivers:
Use statistical modeling to evaluate the impact of variables (e.g., temperature, sector, fuel) on energy demand.
Forecast Energy Consumption:
Predict future energy usage trends using advanced time-series techniques.
Provide Actionable Insights:
Deliver insights to support strategic energy planning and decision-making.
Dataset
The project uses the London Energy and Greenhouse Gas Inventory (LEGGI) dataset:

Columns:
Area: Borough name (e.g., Westminster, Camden).
LEGGI_Year: Year of the recorded energy consumption.
Sector: Sector classification (e.g., Domestic, Industrial and Commercial, Transport).
Fuel: Type of fuel used (e.g., Gas, Electricity).
kWh: Energy consumption in kilowatt-hours.
Features
1. Exploratory Data Analysis (EDA)
Purpose:
Analyze borough-level energy usage trends.
Visualize data using heatmaps and line plots.
Methods:
Aggregated energy consumption by year, sector, and fuel type.
Created heatmaps to compare energy usage across boroughs and sectors.
Key Visualizations:
Energy consumption trends by sector and fuel type.
Heatmap of energy usage by borough and sector.
2. OLS Regression
Purpose:
Quantify the impact of key variables on energy demand.
Steps:
Prepared data by handling missing values, outliers, and multicollinearity.
Encoded categorical variables (sector, fuel type) for regression.
Key Outputs:
Identified significant variables like temperature and sector in predicting energy demand.
3. Autocorrelation Analysis
Purpose:
Detect temporal dependencies and seasonality in energy consumption.
Methods:
Used autocorrelation functions (ACF) to identify lag dependencies.
Incorporated lagged variables into forecasting models.
4. Time-Series Forecasting
Purpose:
Predict future energy consumption trends.
Model:
Built and validated an ARIMA model to forecast energy demand for Westminster’s Domestic sector.
Key Findings:
Predicted a decline in gas usage, driven by efficiency improvements and renewable integration.
Challenges and Solutions
Data Cleaning:
Challenge: Missing and extreme values distorted results.
Solution: Applied forward-filling and log transformations to stabilize the dataset.
Multicollinearity:
Challenge: Strong correlations between predictors caused instability in regression models.
Solution: Used eigenvalue analysis to detect and remove redundant variables.
Autocorrelation:
Challenge: Residuals showed temporal dependencies.
Solution: Included lagged variables to improve model accuracy.
Results
Insights:
Temperature strongly influences energy demand, especially in heating and cooling sectors.
Gas consumption is steadily declining, while electricity usage is stable or rising.
Forecasts:
Predicted a gradual reduction in Domestic energy demand for Westminster over the next five years.
Visualizations
Energy Consumption Trends: Line plots showing sector-wise and fuel-wise trends over time.
Heatmaps: Highlighting energy usage patterns across boroughs and sectors.
Forecasts: Visual comparison of actual vs. predicted energy demand.
Technologies Used
Python Libraries:
pandas: Data manipulation and cleaning.
matplotlib & seaborn: Data visualization.
statsmodels: Statistical modeling and time-series analysis.
