
## Pizza Sales Performance Report
📊 Executive Summary
•	Total Revenue: $817,860
•	Total Orders: 21,350
•	Total Pizzas Sold: 49,574
•	Average Order Value: $38.31
•	Average Pizzas per Order: 2.32

### 🗓️ Peak Sales Insights
Busiest Days:
•	Friday (379 orders) and Saturday (303 orders)
Peak Hours:
•	Orders spike between 12 PM – 1 PM and 7 PM – 8 PM
•	Most orders at 6 PM (218 orders)

### 🧩 Category & Size Analysis
🍕 By Pizza Category:
•	Classic: 27.26%
•	Supreme: 26%
•	Veggie: 24%
•	Chicken: 23%
•	Classic category contributes the most to sales.
📏 By Pizza Size:
•	Regular: 46.18%
•	XLarge: 29.83%
•	Large: 21.91%
•	Others (Medium, XXL): Less than 2%
•	Regular and XL pizzas dominate sales.

### 📈 Sales Trends
Daily Order Trend:
•	Highest on Friday (379)
•	Followed by Sunday (262) and Saturday (303)
Hourly Order Trend:
•	Peaks during afternoon and evening hours
•	Major spikes at 12 PM – 1 PM and 7 PM – 8 PM

### 🏆 Best & Worst Performers
🔝 Top 5 Best-Selling Pizzas:
Pizza Name	Quantity Sold
The Pepperoni Pizza	241
The Barbecue Chicken Pizza	226
The Classic Deluxe Pizza	218
The California Chicken Pizza	198
The Hawaiian Pizza	194
### ❌ Bottom 5 Worst-Selling Pizzas:
Pizza Name	Quantity Sold
The Spinach Supreme Pizza	85
The Chicken Alfredo Pizza	82
The Calabrese Pizza	80
The Chicken Pesto Pizza	79
The Brie Carre Pizza	46
Note: The Brie Carre Pizza had the lowest performance in both quantity and revenue.

### 🧾 SQL Insights Recap
Your SQL queries effectively supported the insights in this report:
•	Revenue, average order value, and quantity calculations are derived using aggregation (SUM, COUNT).
•	Category and size distributions use proportional calculations on SUM(total_price).
•	Trends by day/hour rely on DAYNAME(order_date) and HOUR(order_time) groupings.
•	Best/Worst sellers are based on SUM(quantity * total_price) logic.

## Objectives of Pizza Sales Analysis
1. Measure Overall Business Performance
Track total revenue, order volume, and average order value to assess the financial health of the pizza business.

2. Understand Customer Ordering Behavior
Analyze daily and hourly order trends to identify peak business times.

Determine customer preferences regarding order timing, pizza types, and pizza sizes.

3. Evaluate Product Performance
Identify the top-selling and lowest-selling pizzas by revenue and quantity.

Optimize inventory and menu items based on popularity and sales contribution.

4. Analyze Sales Distribution
Understand how pizza category (e.g., Classic, Supreme, Veggie, Chicken) and pizza size (e.g., Regular, Large, XL) impact total sales.

5. Support Data-Driven Marketing and Promotions
Use insights (e.g., best-selling pizzas, peak hours) to create targeted offers and promotions to boost sales further.

6. Drive Operational Efficiency
Align staffing, inventory, and kitchen operations with peak hours and busy days to improve service quality and reduce waste.

7. Improve Strategic Decision-Making
Enable management to make informed decisions on pricing, product placement, customer engagement, and business expansion using reliable data.

