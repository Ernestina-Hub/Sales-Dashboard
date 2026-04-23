

# Sales Performance & Profitability Analytics Dashboard
 
### Overview
End-to-end data analysis project focused on transforming fragmented sales data into a decision-ready dashboard. Built to enable leadership to quickly identify growth drivers, margin risks, and product performance trends across a 4-year period (2020–2023).

### Business Problem
The Sales and Marketing team lacked a centralized view of performance across revenue, profit, and product categories. Reporting was fragmented, making it difficult to track year-over-year trends, identify underperforming products, and act quickly on trends impacting revenue and margins.


### Solution

Designed and delivered an interactive Tableau dashboard that consolidates key business metrics into a single, intuitive interface. The solution enables real-time performance tracking, trend analysis, and drill-down into product-level insights.
 
### Data Sources

The analysis is based on three primary datasets:

  -  orders.csv – transaction-level sales data (revenue, quantity, dates)
  -  product.csv – product hierarchy and category information
  -  customer.csv – customer segmentation and identifiers
 
 
### Tools Used
- Excel - Data Cleaning transformation and validation 
- Tablau - data modeling, KPI design, interactive dashboard development [Download here](https://tableaupublic.com)
 
### Data Preparation and Modeling

  1. Integrated multiple datasets (orders, products, customers) using relational keys
  
  2. Cleaned missing, inconsistent, and duplicate records
  
  3. Engineered key metrics: Profit, Profit Margin, Year on Year Growth
  
  4. Structured data for time-series and category-level analysis

### Dashboard Features (What Sets This Apart)

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
     



