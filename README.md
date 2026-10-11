= Retail Operations & Inventory Analytics

== Project Overview

I built this Excel project to get more hands-on experience with data analytics and systems analysis. I wanted to see how Excel could be used not just to analyze sales, but also to help a business make inventory purchasing decisions.

I used simulated retail data to build two dashboards: one focused on sales performance and another focused on inventory management.

== Tools Used

- Microsoft Excel
- Power Query
- PivotTables and PivotCharts
- XLOOKUP, FILTER, SORTBY, and dynamic arrays
- Excel formulas and conditional formatting

== What I Built

=== Sales Analysis

I started by cleaning and connecting five datasets using Power Query and Excel formulas.

I analyzed 2,500 sales transactions and created an interactive dashboard that tracks revenue, gross profit, sales channels, product categories, and performance across five North Carolina markets.

I also added a market slicer so the dashboard updates when a different city is selected.

=== Inventory Management

For the second part of the project, I built an inventory reorder model for 60 products.

The model uses daily demand, supplier lead times, safety stock, and available inventory to determine when products need to be reordered.

I also used XLOOKUP, FILTER, and SORTBY to create a purchasing list that automatically updates and ranks products based on stockout risk.

== Key Findings

==Sales Performance==
- Total revenue: $245,124.21
- Gross profit: $115,654.25
- Gross profit margin: 47.18%
- Completed orders: 2,305
- Highest-revenue category: Accessories
- Highest-revenue market: Charlotte

==Inventory Management==
- Products needing reorder: 6
- Suggested purchasing quantity: 707 units
- Estimated purchasing cost: $13,334.20
- Products with backorder concerns: 1
- Additional products at risk: 2

== Business Recommendations

Based on my inventory analysis, I would prioritize reordering the Throw Blanket because the amount reserved for customers is greater than the physical inventory available.

I would also check on supplier delivery times for the Bluetooth Speaker and Wireless Mouse because their estimated inventory could run out before new shipments arrive.

For sales, I would look more closely at the Accessories category to understand why it generates the most revenue and whether it also has the strongest profit margins.

== Reporting Assumptions & Limitations

I only counted completed orders when calculating revenue and gross profit. Cancelled and returned orders were excluded, and shipping revenue was not included.

The inventory model uses estimated demand and supplier lead times, so purchasing recommendations may change if demand or delivery schedules change.

All data in this project is simulated. The purchasing recommendations and financial results are estimates, not actual business savings.

== What I Learned

This project helped me improve my Excel skills and better understand how different business datasets connect.

One of the most useful parts was testing the inventory model by changing stock levels and watching the reorder quantities, costs, and risk classifications update automatically.

It also helped me understand how data analysis and systems analysis work together. The sales dashboard shows how the business performed, while the inventory model helps determine what purchasing decisions should be made next.

=== Automation & Testing

One of the coolest parts of this project was getting the inventory system to update automatically. Instead of manually checking which products need to be reordered, I used Excel formulas to make those decisions based on inventory levels, daily demand, and supplier lead times.

I used XLOOKUP to connect information from different worksheets, along with FILTER and SORTBY to create a purchasing list that automatically updates and ranks products by how urgently they need attention.

I also wanted to make sure the system actually worked, so I tested it by changing the inventory levels of different products. When I lowered a product's available stock, Excel automatically updated the reorder status, suggested purchasing quantity, estimated cost, and stockout risk. The product also appeared in the purchasing priority list without me having to add it manually.

I thought this was one of the most interesting parts of the project because I could see how Excel could be used to build a system that helps make business decisions, rather than just displaying information in a dashboard.
