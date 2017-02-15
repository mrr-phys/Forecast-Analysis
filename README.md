# Forecast-Analysis
Improving forecast accuracy by eliminating human decision views.
Predicting if a human forecast override is better than an automatically generated statistical
forecast on generated synthetic datasets.
These forecasts are often used to help decide how much quantity to buy for any item sold on retail store from vendors/suppliers.

Data is available in at: http://bit.ly/2l8piMK

# Columns:

User: user id

Reason: reason for order

Item: item id

Snapshot: the day the decision by human against forecast is made

Day: the day the decision is going to be applied

Birth: the day item became available for the company

Product_Line: product line

Price: selling price

Has_Promo: if the promotion is available

Model: forecast model that is used such as ARIMA

Sold: unit item sold

Sys_p90: 90 percentile for system forecast

User_p90: 90 percentile for human forecast

Target: response variable to predict (1: to accept human decision and 0 to reject)

