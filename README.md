📊 Pizza Sales Business Intelligence Analysis

Tools: Power BI | Tableau | SQL-style Data Modeling | DAX

📌 Project Overview
This project analyzes pizza sales data to uncover revenue patterns, demand behavior, and product performance.

The same dataset was explored using both Power BI and Tableau to demonstrate how different BI tools influence visual storytelling, layout, and insight communication.

🗂 Dataset
The analysis combines four CSV files:
- Orders
- Order Details
- Pizzas
- Pizza Types
These were joined using appropriate keys and relationships to form a unified analytical model.

🔧 Data Preparation
- I Joined datasets using order_id and pizza_id
- I Cleaned inconsistent values and formats
- I Created helper columns:
   - Order Hour
   - Day of Week
   - Month
- I Validated data types for accurate aggregation

📐 Data Modeling
- Star-schema–style relationships
- Fact table: Sales transactions
- Dimension tables: Pizza, Category, Date

This structure supports flexible slicing and aggregation.

🧮 DAX Measures (Power BI)
Key measures created using DAX:
- Total Revenue
- Total Quantity Sold
- Total Orders
- Average Pizza Price
- Revenue Share
- Peak Hour Sales
DAX was used to handle time-based calculations and KPIs.

📊 Visual Analysis
Insights explored include:

- Monthly revenue trends and seasonality
- Peak sales hours and days of the week
- Best and worst performing pizzas (by revenue & quantity)
- Revenue contribution by category
- Product pricing behavior


🧠 Key Takeaways
- Fridays generate the highest revenue
- Sales peak during lunch and dinner hours
- Classic pizzas contribute the most revenue
- Some menu items consistently underperform and may need review

⚖️ Power BI vs Tableau

Power BI: Strong for structured KPIs, DAX-driven metrics, and report-style dashboards

Tableau: Excels in exploratory analysis, heatmaps, and visual storytelling

Both tools offer unique strengths depending on the business goal.

👤 Author

Precious Nwachukwu
Business Analyst | Data Science | HR Background 
📍 Nigeria
