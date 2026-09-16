A Tableau analysis of a multi-region sales dataset, built to answer three core business questions: which regions drive profit, which products drive revenue, and how product lines compare against each other. Each view is designed to lead with a takeaway rather than just a chart.

Business questions
Which regions are the most (and least) profitable, across all customer segments?
Which individual products generate the most revenue, and how much of total sales do the top performers account for?
How do the four product categories compare on revenue, in the order the business actually cares about them?
Views
Regional Profit Ranking

"Western U.S. Leads Profits, while Canada Trails"

A ranked bar chart of total profit by region across all customer segments (Consumer, Corporate, Small Business). The view is sorted so the highest- and lowest-profit regions are immediately visible, surfacing where the business is over- or under-performing geographically.

Top 10 Products

A ranked bar chart of the ten best-selling products by revenue, isolated with a Top-N filter (SUM of Sales Amount, descending). This narrows a full product catalog down to the handful of SKUs that matter most for revenue conversations.

Product Category Ranking

A bar chart of revenue by product category, deliberately ordered Bikes → Components → Clothing → Accessories to mirror how the business prioritizes its lines, rather than a purely value-sorted order.

What this project demonstrates
Data connection & modeling: live connection to an Excel source (SalesData table, 17 fields spanning orders, customers, products, and profitability metrics)
Analytical filtering: categorical filters, a Top-N (rank-based) filter, and business-defined manual sort order
Sorting & ranking logic: dimension-by-measure sorts to surface leaders and laggards at a glance
Insight-driven titling: worksheet titles written as takeaways ("Western U.S. Leads Profits, while Canada Trails") instead of generic labels, so a viewer gets the conclusion before reading the chart
Data

The underlying dataset (BAI501_Tableau_Sales_Data.xlsx) contains order-level sales records with fields for order/customer identifiers, customer segment, region, country, product category/subcategory/name, pricing, quantity, discount, cost, profit, and customer income. It is coursework/practice data used for skill-building, not production business data.
