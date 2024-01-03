
# Online Retail Customer Segmentation

This repository contains code and data for a Customer Segmentation in Online Retail Project. The project uses a variety of machine learning models to perform Clutering / Segmentation of customers for an online retail store.

This is a transnational data which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

| Variable Name | Role | Type | Demographic | Description | Units |	Missing Values|
|---------------|------|------|-------------|-------------|-------|---------------|
|InvoiceNo|ID|Categorical| |a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation| |no|
|StockCode|ID|Categorical| |a 5-digit integral number uniquely assigned to each distinct product| |no|
|Description|Feature|Categorical| |product name| |no|
|Quantity|Feature|Integer| |the quantities of each product (item) per transaction| |no|
|InvoiceDate|Feature|Date| |the day and time when each transaction was generated| |no|
|UnitPrice|Feature|Continuous| |product price per unit| sterling |no|
|CustomerID|Feature|Continuous| |a 5-digit integral number uniquely assigned to each customer| |no|
|Country|Feature|Continuous| |the name of the country where each customer resides| |no|

This Notebook mainly has three sections :-

a. Data Cleaning and Exploratory Data Analysis

b. RFM (Recency, Frequency, Monetary) Analysis

c. Modeling

d. Conclusion

Dataset Info :- https://archive.ics.uci.edu/ml/datasets/online+retail