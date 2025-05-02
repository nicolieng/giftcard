# giftcard

## Problem Statement 
To support strategic planning and resource allocation, this project aims to forecast monthly gift card purchase values for the remainder of 2022, using historical purchase data from January 1, 2021, to January 14, 2022. The goal is to equip the Finance team with accurate, currency-specific projections to better manage cash flow, plan inventory, and optimize marketing efforts.

## What are the highlights from this project?
This project focuses on time series analysis and forecasting, where I processed historical data and developed predictive models using classical approaches—AR, ARIMA, SARIMA—as well as Meta's Prophet model. After comparing and validating these methods, I identified the optimal model to help stakeholders anticipate future performance, enabling more efficient resource allocation and strategic planning. Despite initial challenges with model selection due to data constraints, my efforts led to accurate forecasts of total gift card purchases (by denomination) across four currencies, delivering remarkable value to the Finance team.

## What to expect in this repository?
1. Order_items.csv, a dataset which contains information on individual gift card, includes variables such as unique id, created date, product currency, sender name, delivery type, recipient name, recipient email, recipient address, and more. The data ranges from 01-01-2021 to 01-14-2022.

2. Digital_card_orders.csv, the parent record of Order_items.csv, includes data such as unique id, created date, order_id, status, country and language. All data ranges from 01-01-2021 to 01-14-2022.
   
3. A jupyter notebook in storing all the scripts and relevant charts for data manipulation, data pre-processing, time series decomposition and analysis, forecast modeling, model fine-tuning, as well as the end result. 


## What is the source of the data?
The data files are provided by a company who specializes in providing technology solutions in revolutionalizing the digital gift card industry. 
