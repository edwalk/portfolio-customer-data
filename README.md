# Online Shop Customer Sales Data

## Status
- Project 1: Completed (15/05/2023)

Please check the Project 1 - Daily Monitoring Dashboard to download the [Excel file](https://edward-walker.space/portfolio/files/monitoring_dashboard.xlsx) or a [PDF extract](https://edward-walker.space/portfolio/files/monitoring_dashboard_pdf.pdf).

- Project 2: Not started (15/05/2023)

## Dataset
 This portfolio project uses a dataset from Kaggle: Online Shop Customer Sales Data
 https://www.kaggle.com/datasets/onlineretailshop/online-shop-customer-sales-data

## Dataset variables
- Customer_id = unique customer id
- Age = customer's age
- Gender = 0: Male, 1: Female
- Revenue_Total = total sales by customer
- N_Purchases = number of purchases to date
- Purchase_DATE = date latest purchase, dd.mm.yy
- Purchase_VALUE = latest purchase in €
- Pay_Method = 0: Digital Wallets, 1: Card, 2: PayPal, 3: Other
- Time_Spent = time spent (in sec) on website
- Browser = 0: Chrome, 1: Safari, 2: Edge, 3: Other
- Newsletter = 0: not subscribed, 1: subscribed
- Voucher = 0: not used, 1: used

## Dataset sample size

n = 65796

## Project 1 - Daily Monitoring Dashboard

The aim of this segment of the project is to create a dashboard that could hypothetically be used by the business to monitor their online shop activity daily, based on the data gathered in this dataset. While the dataset used here is static, the dashboard will be created in a way that would allow for ongoing updates to the dataset, simulating a live business environment where the online shop customer sales data would be updated at regular intervals.

### Skills displayed
- Data Source insertion in PowerQuery
- Data normalization and cleaning in PowerQuery
- Pivot Tables
- Pivot Charts
- Dynamic Formulas & data points
- Dashboard Design
- Business analysis

The dashboard displays the following:

### Customers

- Average age
- Age group breakdown
- Gender split
- Average Time since last purchase 
- Proportion of returning customers (more than a single purchase)
- Proportion of single-purchase customers (only 1 purchase) 
- Proportion of active returning customers (people with more than one purchase, with their last purchase made less than 90 days ago)
- Proportion of lapsed returning customers (people with more than 1 purchase, with their last purchase made more than 90 days ago) 
- Proportion of new customers (people with a single purchase within the last 90 days) 
- Proportion of lapsed new customers (people with a single purchase more than 90 days ago) 

### Total Sales
- Count 
- Average number of sales per customer 

### Latest Sales
- Average amount of latest purchase per customer 
- Breakdown of different payment methods used 
- Proportion of latest sales involving voucher usage
- Average time spent on website 
- Breakdown of different browsers used
- Proportion of newsletter subscribers

Because the data does not include purchase details outside of the latest purchase made by a customer, it is not possible to provide aggregate data on elements such as voucher usage, newsletter subscription status or time spent on website for the entire purchase history of each customer.

## Project 2 - Analysis
The aim of this segment of the project is to analyse the data, identify correlations and potential causations and suggest data-driven next steps to improve sales and customer retention. 

I will look to answer the following questions:

- Do specific age groups or genders make more purchases on the website than others?
- Have specific age groups spent more money on their latest purchase than others?
- Are specific age groups more likely to use certain payment methods over others?
- Are specific age groups more likely to be lapsed customers (more than 180 days since last purchase)?
- Are specific genders more likely to be lapsed customers (more than 180 days since last purchase)?
- Does the customer's browser impact the value of their latest purchase, the time spent on the website, and the total number of purchases made?
- Does voucher usage increase the average value of a customer's latest purchase?
- Does subscribing to the newsletter increase or decrease the amount of time spent on the website for each customer's latest purchase?

These questions would allow an analyst to make data-driven recommendations on next steps to increase customer acquisition and retention and increase sales during the 2022 calendar year.

