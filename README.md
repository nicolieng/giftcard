# giftcard

## 📌 Problem Statement 
To support strategic planning and resource allocation, this project aims to forecast monthly gift card purchase values for the remainder of 2022, using historical purchase data from January 1, 2021, to January 14, 2022. The goal is to equip the Finance team with accurate, currency-specific projections to better manage cash flow, plan inventory, and optimize marketing efforts.

## ✨ Project Highlights
Applied time series forecasting using ARIMA, SARIMA, and Prophet models.

Processed and modeled gift card purchase data individually across four currencies to capture distinct seasonality and trend patterns.

Compared model performance through validation metrics and selected the best-performing model for each currency.

Tackled challenges such as sparse data periods and evolving demand patterns, ensuring model robustness.

Built reproducible workflows for data preprocessing, model training, evaluation, and visualization.

## 📈 Outcomes & Impact
Using time series models (ARIMA, SARIMA, Prophet), we achieved an X% improvement in forecast accuracy compared to previous methods. This enabled the Finance team to:

Accurately project monthly gift card purchases across 4 currencies for the rest of 2022.

Optimize cash flow management and adjust inventory levels in anticipation of seasonal spikes.

Support more informed budgeting and marketing decisions for key promotional periods.

Identify a trend of increased demand during Q4, allowing stakeholders to proactively plan resources.



## 📂 What to Expect in This Repo
1. Order_items.csv, a dataset which contains information on individual gift card, includes variables such as unique id, created date, product currency, sender name, delivery type, recipient name, recipient email, recipient address, and more. The data ranges from 01-01-2021 to 01-14-2022.

2. Digital_card_orders.csv, the parent record of Order_items.csv, includes data such as unique id, created date, order_id, status, country and language. All data ranges from 01-01-2021 to 01-14-2022.
   
3. A jupyter notebook in storing all the scripts and relevant charts for data manipulation, data pre-processing, time series decomposition and analysis, forecast modeling, model fine-tuning, as well as the end result. 


## 🔍 Data Source
Gift card transaction records collected internally between January 1, 2021, and January 14, 2022. Each record includes purchase amount, currency, timestamp, and more.
The data is provided by a company who specializes in providing technology solutions in revolutionalizing the digital gift card industry. 
