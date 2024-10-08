# Store Sales Forecasts for Favorita

Favorita, a large Ecuadorian-based grocery retailer is looking to help improve supply chain efficiency and planning by predicting product sales. We aim to forecast 15 days out to help make supply chain decisions that can help planning teams better position their supply chain across their stores.

# Modeling hypothesis and assumptions
### - Seasonality and Trend
We hypothesize that this data contains seasonality and trend.
### - Modeling Hypothesis
A traditional model such as ARIMA should capture both seasonality and trend, while a more complex machine learning model such as XGBoost should be able to capture variables that are noted as very important for the macroeconomic conditions in Ecuador such as oil price, holidays, and promotions.
Together we hypothesize that these models will capture both the traditional aspects of grocery sales as well as the unique attributes that affect the Ecuadorian economy and consumer choices.
### - Assumptions
We assume the grocery sales data in Ecuador exhibits seasonality and a long-term trend influenced by factors like holidays, inflation, and population growth, with external variables such as oil prices and promotions significantly impacting sales. Models like ARIMA capture these patterns, while XGBoost accounts for macroeconomic conditions and consumer behavior.

# Data Descriptions and Properties
- Holidays & Events : Date, type of event, location, and additional information such as whether the event was transferred to another date.
- Store Information : Store ID, location (city and state), store type and cluster group to which the store belongs.
- Transaction Data : Number of transactions that occurred a specific stores on given dates. WTI Crude Oil Price : WTI Crude oil prices with the date.
- Product families & Sales : Product families and promotions, showing the sales figures for different products families at specific stores on given dates.

# Data processing and EDA
<img width="1099" alt="image" src="https://github.com/user-attachments/assets/c00f9257-90d2-4e44-95c7-4d05b23919e3">
