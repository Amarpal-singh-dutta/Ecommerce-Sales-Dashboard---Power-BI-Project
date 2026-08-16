# Ecommerce-Sales-Dashboard-Power-BI-Project

## About This Project
I built this dashboard to analyze 2 years of ecommerce sales data (2021-2022) 
and find out how the business performed, where the profit is coming from, 
and what changed year over year.

## Business Question
The company wanted to know:
- Are sales going up or down compared to last year?
- Which product category makes the most profit?
- Are we selling more items or fewer items than before?
- Which products sell the best, and which barely sell at all?

## Data Used
- 113,270 orders from Jan 2021 to Dec 2022
- Columns: order date, sales, profit, quantity, category, product name, 
  customer segment, region, shipping info
- Tool used: Power BI (Power Query for cleaning, DAX for calculations)

## What I Did (Approach)
1. Cleaned the data - fixed date format issues (dates were in DD-MM-YYYY format)
2. Built a separate Calendar table to properly calculate YTD (year-to-date) 
   and PYTD (previous year-to-date)
3. Wrote DAX measures for Sales, Profit, Quantity, and Profit Margin, 
   plus their YoY (year-over-year) % change
4. Built visuals: KPI cards, monthly trend chart, category breakdown table, 
   top 5 and bottom 5 products, profit by category chart
5. Added filters so the whole dashboard updates by customer segment 
   (Consumer / Corporate / Home Office)

## Key Findings
- **Sales stayed almost the same** - $11.63M in 2021 vs $11.53M in 2022, 
  only 0.83% lower
- **But order quantity dropped 7.29%** (115,648 units → 107,218 units)
- **Profit margin actually improved** - from 10.99% to 11.58% - meaning 
  each order became more profitable, even with fewer orders
- **Office Supplies makes the most profit** ($1.6M total), way more than 
  Furniture ($0.6M) or Technology ($0.5M) - even though all 3 categories 
  have almost the same profit margin (~11%). This is because Office 
  Supplies sells in much higher volume.
- **Furniture grew the fastest** (+0.73% YoY), while Technology and 
  Office Supplies both dropped slightly
- Best-selling products are cheap, everyday office items (staples, 
  envelopes, paper) - these sell often but in small amounts

## My Recommendation
Since Furniture is growing the fastest, it's worth investing more in that 
category next year. At the same time, Office Supplies should stay protected 
since it brings in the most total profit, even with a normal margin. 
Because customers are buying fewer but higher-value orders, the company 
could try bundling products together or offering upsells to keep growing 
profit even if order count keeps dropping.

 ## Dashboard Preview
   ![Dashboard Screenshot](Screenshot%20(991).png)
   
## Tools Used
Power BI Desktop, DAX, Power Query

## File
Open `Ecommerce_sales_analysis(1).pbix` in Power BI Desktop to view/edit 
the live dashboard.
