# Walmart Sales Time Series
# Business Overview
## What is Time Series Forecasting?
A sequence of data points collected often at a constant time interval of a given entity is known as time series. The measure question asked by any business is “how did the past influence the future?”. Forecasting is a process by which the future observation is estimated by using historical data. A statistical method that is used to analyze the data taken over time to forecast the future is known as time series forecasting. It is used to analyze time-based patterns in data and hence to determine a good model to forecast future behavior. Basically time series connect the past, present, and future.

## Use Cases / Aim
From supply chain, stocks, biomedical monitoring etc. forecasting is used everywhere. For this project there are two main use cases for forecasting. The first being store sales prediction to manage inventory demand and plan ahead accordingly. The second is ride-hailing demand for pricing and supply chain management. One of the importance of forecasting is if a holiday comes over how one should plan store sales to get maximum sales hence the profit.

## Data Description
The dataset used is Walmart store sales data. Walmart is an American multinational retail corporation that operates a chain of hypermarkets, department stores, and Grocery stores. The dataset provided is historical sales data for 45 Walmart stores located in different regions. Each store contains many departments. Four different datasets are provided

- Stores.csv: This file contains information about the 45 stores,indicating the type and size of the store.
- Train.csv: This is the historical training data, which covers 2010-02-05 to 2012-11-01.
- Test.csv: This file is identical to train.csv, except for the weekly sales which have to be predicted.
- Features.csv: This file contains additional data related to the store, department, and regional activity for the given dates.
## Column Description
- Store - the store number 
- Date - the week 
- Dept - the department number 
- Temperature - the average temperature in the region 
- Fuel_Price - the cost of fuel in the region 
- MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011 and is not available for all stores all the time. Any missing value is marked with an NA. 
- CPI - the consumer price index 
- Unemployment - the unemployment rate 
- IsHoliday - whether the week is a special holiday week 
- Weekly_Sales - sales for the given department in the given store
