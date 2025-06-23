# Forecasting-Microsoft-Stock-Price.
📈 Stock Price Prediction (July–December 2025) — Microsoft (MSFT)
📝 Project Overview
This project aims to forecast the stock prices of Microsoft (MSFT) for the period July to December 2025 using historical data and time series modeling. The forecasts are visualized in an interactive Power BI dashboard to explore trends and insights.

# 📊 Data Source
Stock: Microsoft Corporation (MSFT)

Source: Yahoo Finance

Time Period: October 1988 - June 2025

Frequency: Daily stock prices

# 🔍 Methodology
1. Data Collection

- Collected historical MSFT stock price data using Yahoo Finance Python API.

- Stored relevant fields: Date, Open, High, Low, Close, Adj Close, Volume.

2. Forecasting Model

- Used Facebook Prophet model for time series forecasting.

- Trained on data from 1988 to June 2025.

- Predicted stock prices for 6 months ahead (July to December 2025).

- Focused on forecasting the 'Close' price.

3. Data Export

- Exported actual and forecasted data to Excel for easy integration with Power BI.

4. Visualization in Power BI

Created interactive visualizations including:

- forecasted closing prices

- Monthly average trends

- Volume analysis

- Forecast confidence intervals
  
- Last 7 and 30 days analysis

# 🛠 Tools & Technologies
Python: Data processing and Prophet modeling

Libraries: yfinance, pandas, prophet, matplotlib

Power BI: Dashboard for interactive visualization

Excel: Used as a bridge for importing forecasted data into Power BI

# 📌 Key Insights
- Provided a clear 6-month forecast for Microsoft stock prices.

- Enabled visual analysis of potential market trends.

- Illustrated the usefulness of Prophet for stock time series prediction.


# 🔮 Future Work
1. Explore other models like ARIMA, LSTM for comparison.

2. Include other stocks for portfolio-level forecasting.

3. Add live data refresh with Power BI for up-to-date trends.

# 🙋‍♂️ Author
Sudipta Mitra
Pursuing B.Sc. in Data Science
