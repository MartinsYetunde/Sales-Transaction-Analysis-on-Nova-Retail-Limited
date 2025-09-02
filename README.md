# Sales-Transaction-Analysis-on-Nova-Retail-Limited
The dataset, analyzed using Python, contains 110 sales transactions across 11 columns: TransactionID, Date, City, CustomerID, CustomerType, Category, UnitsSold, UnitPrice, Revenue, Discount, and Profit. It spans 4 cities, 77 customers, and 3 categories, with no missing values. Average revenue is 268K, supporting robust sales insights.

<img width="569" height="293" alt="Screenshot 2025-08-20 134406" src="https://github.com/user-attachments/assets/4c936546-56f1-44e4-86da-de77968884d8" />
<img width="584" height="287" alt="Screenshot 2025-08-20 134301" src="https://github.com/user-attachments/assets/446089ba-28a0-4834-a174-d925e845ad4f" />

# Executive Summary
NovaRetail Ltd.’s sales analysis highlights Electronics as the leading revenue driver, with Lagos and Abuja as key markets. Seasonal peaks, particularly in September 2024, reveal opportunities for targeted promotions. Returning customers generate more revenue than new ones, while top-performing sales reps significantly outperform peers. Strategic actions in inventory management, customer loyalty, and sales team optimization can enhance growth and competitiveness.

# Business Understanding
Context: NovaRetail operates across Nigeria, offering Electronics, Appliances, and Accessories.
Challenge: Management lacked visibility into sales performance, customer behavior, seasonal trends, and sales force contributions.

## Key Questions:
Which cities and regions generate the most revenue?
Which product categories are most profitable?
How much revenue comes from new vs. returning customers?
Are there identifiable seasonal trends in sales?
Which sales reps contribute most, and where is improvement needed?
Objective: Provide insights to improve inventory planning, marketing allocation, customer retention, and sales team effectiveness.

## Data Understanding
Scope: Transactions across multiple Nigerian cities, customer types, categories, and sales reps.
# Features:
Date, City, Customer ID, Customer Type
Category (Electronics, Appliances, Accessories)
Sales Rep, Units Sold, Unit Price, Discount, Revenue
Timeframe: Transactions up to September 2024.

## Methodology
# Data Processing
Imported dataset using Python (pandas).
Converted date fields for monthly/seasonal analysis.
Cleaned data and verified revenue consistency.
Derived new metrics (e.g., Average Revenue per Customer, Repeat Purchases).
# Analysis Techniques
Grouped data by City, Category, Customer Type, Month, and Sales Rep.
Calculated customer loyalty and value metrics.
Conducted trend, segmentation, and profitability analysis.
# Visualization
Used matplotlib & seaborn for bar charts, line graphs, and pie charts.
Displayed sales trends, city/category revenue, and sales rep performance.

# Key Insights & Recommendations
Sales Performance: Total revenue strong; avg. revenue per customer = ₦383,390.
Recommendation: Segment customers to tailor loyalty programs.
Customer Behavior: Returning customers dominate revenue; new customers growing.
Recommendation: Launch loyalty program for returnees + welcome offers for new customers.
City-Level : Lagos leads (₦9.3M), followed by Abuja; smaller cities underperform.
Recommendation: Focus inventory/marketing on top cities; build awareness elsewhere.
Product Insights : Electronics = top revenue; Accessories = high sales volume, lower revenue.
Recommendation: Ensure Electronics stock availability; bundle Accessories to boost sales.
Seasonal Trends: Peak in September 2024 (₦4.7M).
Recommendation: Align campaigns with festive/peak months.
Sales Rep Performance: Abdul Salim lead revenue generation.
Recommendation: Incentivize top reps; use their strategies to train underperformers.

# Conclusion
NovaRetail’s sales performance is driven by Electronics, Lagos/Abuja markets, returning customers, and top-performing sales reps. Seasonal peaks highlight opportunities for well-timed campaigns. By prioritizing customer loyalty, inventory optimization, city-focused marketing, and sales force development, NovaRetail can strengthen its market position and achieve sustained growth.
