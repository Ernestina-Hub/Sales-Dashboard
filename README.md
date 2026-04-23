

# Sales Performance & Profitability Analytics Dashboard
 
### Business Problem
The Sales and Marketing team lacked a centralized view of performance across revenue, profit, and product categories. Reporting was fragmented, making it difficult to track year-over-year trends, identify underperforming products, and make timely, data-driven decisions.


### Objective

Develop an interactive dashboard that provides a clear, consolidated view of sales performance from 2020–2023, enabling stakeholders to monitor growth, profitability, and product-level performance.
 
### Data Sources

The analysis is based on three primary datasets:

  -  orders.csv – transaction-level sales data (revenue, quantity, dates)
  -  product.csv – product hierarchy and category information
  -  customer.csv – customer segmentation and identifiers
 
 
### Tools Used
- Excel - Data Cleaning transformation and validation [Download here](https://microsoft.com)
- Tablau - dashboard design, data modeling, and visualization [Download here](https://tableaupublic.com)
 
### Data Preparation

The following steps were completed during the data preparation phase:

  1. Merged datasets using common keys (Product ID, Customer ID)
  
  2. Handled missing values and removed duplicates
  
  3. Created calculated fields (e.g., profit, profit margin, year-over-year growth)

### Purpose
The purpose of the sales dashboard is to present an overview of the company's year on year revenue growth, profitability and product-level performance in order to analyze year-over-year sales performance and understand sales trends.

### Key Requirements from stakeholders:

### KPI Overview
Display a summary of total sales, profits and quantity for the current year and the previous year.
### Sales Trends
– Present the data for each KPI on a monthly basis for both the current year and the previous year.

– Identify months with highest and lowest sales and make them easy to recognize.

### Product Subcategory Comparison
– Compare sales performance by different product subcategories for the current year and the previous year.
– Include a comparison of sales with profit.

### Weekly Trends for Sales & Profit
– Present weekly sales and profit data for the current year.
– Display the average weekly values.

– Highlight weeks that are above and below the average to draw attention to sales & profit performance.


<img width="940" height="617" alt="image" src="https://github.com/user-attachments/assets/799e193b-eb5a-4178-b933-c4fab2b61e7b" />

## Key insights 
1.	Strong YoY growth across all KPIs 
      - Sales: +20.36%
      -  Profit: +14.24% 
      -  Quantity: +26.83%

#### Volume is growing faster than profit, indicating margin pressure. 


2.	Profitability not scaling with sales 
    - Profit growth < Sales growth → potential discounting, cost increases, or low-margin product mix.

3.	Subcategory performance imbalance 
    - High sales ≠ high profit in some categories (e.g., Copiers showing losses despite sales)
    - A few subcategories are driving most of the profit.
  
4.	Clear top and bottom performers
   -  Strong contributors: Phones, Chairs (high sales + positive profit)
   -  Underperformers: Copiers, Machines, Tables (loss or weak margin) 

5.	Seasonality and volatility
     -  Sales and profit fluctuate significantly over time.
     -  Peaks toward year-end suggest seasonal demand
  
6.	Below-average performance periods
     - Several periods fall below average sales and profit benchmarks → inconsistency in performance


## Actionable recommendations

1.	Improve margin management 
    -  Review pricing and discount strategies
    -  Investigate cost drivers in low-margin categories 
2.	Fix or exit loss-making subcategories 
    -  Deep dive into Copiers/Machines: 
        -  Supplier costs
        -  Discounting patterns
        -  Return rates 
3.	Double down on high-performing categories 
    -  Increase inventory, promotions, and visibility for top profit drivers (e.g., Phones, Chairs) 
4.	Optimize product mix 
    -  Shift focus toward high-margin items instead of just high-volume sales 
5.	Address demand volatility 
    - Use trend insights for:
    - Better forecasting
    - Inventory planning
    - Staffing alignment during peak periods 

6.	Set performance benchmarks
    - Use average sales/profit lines to:
          -  Track underperformance early
          -  Drive weekly/monthly targets 
8.	Customer/order-level analysis (next step) 
    -  Identify: 
        -  High-value customers
        -  Repeat purchase patterns
        -  Profit per customer
     



