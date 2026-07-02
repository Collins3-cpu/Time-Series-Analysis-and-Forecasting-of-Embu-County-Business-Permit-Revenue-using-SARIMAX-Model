# Time-Series-Analysis-and-Forecasting-of-Embu-County-Business-Permit-Revenue-using-SARIMAX-Model

Time Series Analysis and Forecasting of County Revenue Streams using SARIMAX
This project analyzes historical monthly revenue data from Embu County, Kenya, focusing on key sources like Single Business Permits, Cess, Market Fees, and others. It includes data cleaning, exploratory visualization, and forecasting using SARIMAX models.

📋 Project Overview

Data Source: Compiled Data.csv (monthly revenue records from 2017 onwards)

Key Focus: Single Business Permit revenue forecasting

Technologies: Python (pandas, statsmodels, matplotlib), Jupyter Notebook

Model: SARIMAX (Seasonal Auto-Regressive Integrated Moving Average with eXogenous factors)

📈 Key Insights
Revenue Composition

Main Contributors: Single Business Permit, Cess, Advert Fees, Market Fees, House Stalls, Bus Park, Land Rates, etc.

Trends: Significant seasonal patterns observed in permit collections and other fees.

Data Quality: Cleaned missing values; datetime conversion for time series analysis.

Single Business Permit Performance

Historical fluctuations with potential seasonal cycles (e.g., annual peaks).

Overall, an upward or stable trend depending on economic factors.

High variability is influenced by business activity, regulatory changes, and external events.

Forecasting Results

SARIMAX model fitted with order (1,0,0) and seasonal order (0,1,1,12) — capturing both trend and yearly seasonality.A 

A 25-month forecast was generated showing the projected revenue trajectory.

The model highlights expected growth or stabilization in permit revenue.

🔍 Analysis Highlights

Time Series Visualization: Historical plot of Single Business Permit revenue showing trends and volatility.

Forecast Plot: Projected values for future periods with confidence in seasonal modeling.

Decomposition: Observed components analyzed for trend, seasonality, and residuals.

💡 Recommendations

Policy & Revenue Enhancement:

Strengthen business registration drives to boost Single Business Permit collections.
Introduce digital payment systems to improve compliance and reduce leakages.

Seasonal Planning:

Align enforcement and awareness campaigns with peak revenue months identified in the analysis.
Use forecasts for budgeting and resource allocation.

Diversification:

Explore growth opportunities in underperforming streams (e.g., Advert Fees, Technical Planning Fees).
Monitor external factors (inflation, business climate) impacting revenue.

Model Improvements:

Incorporate exogenous variables (e.g., GDP growth, inflation rates, number of registered businesses).

Experiment with alternative models (Prophet, LSTM) for comparison.

Regular model retraining with new monthly data.

Operational Recommendations:

Automate reporting dashboards for real-time revenue monitoring.

Conduct sensitivity analysis on forecast assumptions.

🛠️ Technologies Used

Data Handling: pandas, numpy

Modeling: statsmodels (SARIMAX)

Visualization: matplotlib

Environment: Jupyter Notebooks
