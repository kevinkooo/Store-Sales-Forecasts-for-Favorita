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
<img width="1096" alt="image" src="https://github.com/user-attachments/assets/5c2e8b27-4c3a-49ae-b64a-d81cdf71728e">
<img width="1055" alt="image" src="https://github.com/user-attachments/assets/2d8beab9-3c92-42ac-925d-66150892bf3a">

# Feature Engineering
## Holiday, Oil Prices and Promotion
<img width="1237" alt="image" src="https://github.com/user-attachments/assets/22319f00-5230-4de4-8423-388fb3779f60">

## DTW to Cluster Food Categories
<img width="1222" alt="image" src="https://github.com/user-attachments/assets/4b6e05f5-5906-46b8-bb6c-067ca4417af1">
<img width="1236" alt="image" src="https://github.com/user-attachments/assets/bd4699c5-b1dc-4d7b-8562-254ec03cc815">

# Proposed Model and Approaches
<img width="1133" alt="image" src="https://github.com/user-attachments/assets/401e12ba-2585-4f4d-a1c7-8ed8a8b55982">

# Selected Model
<img width="1204" alt="image" src="https://github.com/user-attachments/assets/c2248b13-1d7d-49c3-a47e-17c09ca22da6">

# Insight Recommendations and Future Works
<img width="1257" alt="image" src="https://github.com/user-attachments/assets/b4946bb0-85fb-4309-8dd4-6fa315c97077">



