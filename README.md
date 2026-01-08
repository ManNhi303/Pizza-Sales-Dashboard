🍕 Pizza Sales Performance Analysis (Power BI & SQL)
![alt text](https://img.shields.io/badge/Project-Data_Analysis-blue?style=for-the-badge)

![alt text](https://img.shields.io/badge/Tools-SQL_|_Power_BI_|_Excel-orange?style=for-the-badge)
📌 Project Background
This project aims to analyze a year's worth of pizza sales data to identify trends, popular products, and revenue drivers. To ensure 100% data accuracy, I integrated SQL Server to validate all KPIs and metrics before visualizing them in Power BI.
Dataset Source: Pizza Sales Dataset (Kaggle)
Data Scale: ~48,000+ transaction records.
⚙️ Technical Workflow
Data Extraction & Cleaning: Used SQL and Power Query to handle missing values and format data types.
Data Validation (SQL): Developed a comprehensive set of SQL queries to calculate Total Revenue, Average Order Value, and Top Sellers. These results were used as a "source of truth" to verify Power BI measures.
Data Modeling: Created relationships and calculated DAX measures (Total Sales, Order Frequency, etc.).
Dashboard Design: Built an interactive 2-page report focusing on Sales Overview and Product Performance.
📊 Dashboard Key Features
Overview Page: Real-time tracking of 5 core KPIs (Revenue, Total Orders, Units Sold, AOV, and Pizzas per Order).
Trend Analysis: Visualizing sales velocity by day of the week and month.
Best/Worst Sellers: A dedicated breakdown of the Top 5 and Bottom 5 pizza performers across three different metrics (Revenue, Quantity, and Orders).
💡 Key Business Insights
1. Sales Trends & Peak Periods
Busiest Days: Orders peak significantly on Fridays and Saturdays. These days see a high volume of transactions, suggesting that pizza is a primary "weekend treat" for customers.
Peak Hours: Order volume surges during Lunch (12 PM - 1 PM) and Dinner (6 PM - 8 PM).
Seasonal Peaks: The months of January and July recorded the highest sales. This could be attributed to New Year celebrations and summer holiday promotions.
2. Product Performance
The "Star" Product: The Thai Chicken Pizza contributes the Maximum Revenue, indicating it is a high-value item that drives the bottom line.
The "Crowd Favorite": The Classic Deluxe Pizza is both the Most Ordered and has the highest unit sales, proving it is a staple product with high customer loyalty.
The "Underperformer": The Brie Carre Pizza consistently ranks as the Worst Seller in terms of revenue, quantity, and order frequency.
3. Category & Size Preferences
Top Category: The Classic Category is the most popular, contributing over 27% of total sales volume.
Size Distribution: Customers have a strong preference for Large (46%) and Medium (30%) sizes. Smaller sizes and X-Large sizes show much lower demand.
🚀 Strategic Recommendations
Staffing: Optimize kitchen and delivery shifts to be at full capacity during the Friday/Saturday "Prime Time" (6 PM - 8 PM).
Menu Optimization: Since Brie Carre has the lowest performance, the business should consider a recipe rework, a limited-time discount to clear inventory, or replacing it with a more trendy flavor.
Promotional Strategy: Bundle the "Classic Deluxe" (Popularity leader) with high-margin sides to increase the Average Order Value (AOV).
Inventory Management: Focus stock levels on Large and Medium crusts to prevent stockouts of the most popular sizes.
📂 Repository Contents
Pizza_Sales_Report.pbix - The final interactive Power BI dashboard.
SQL_Queries.docx - The full collection of SQL scripts used for data verification and KPI extraction.
Dataset/ - Raw data files from Kaggle.
Developed by: [Your Name]
Contact: [Your Email / LinkedIn Profile Link]
