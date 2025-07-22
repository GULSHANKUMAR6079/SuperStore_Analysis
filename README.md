📊 Superstore Sales Analysis Dashboard

A complete business intelligence solution built using Power BI, MySQL, and the Superstore dataset, aimed at providing deep insights into sales performance, customer behavior, shipping trends, and profitability.

📁 Project Overview

This project is a Data Analytics and BI case study on a fictional retail company. It answers real stakeholder questions using visual dashboards, KPIs, SQL queries, and DAX measures.

Key components:

🧶 MySQL for data preprocessing and analysis

📊 Power BI for interactive visual dashboards

📁 Superstore dataset as the data source

🚀 Features

✅ Cleaned, normalized dataset (handled date formats, nulls, duplicates)✅ Created custom calculated fields like Order Year, Month, Ship Delay, AOV, etc.✅ KPI Cards for total Sales, Profit, YoY Growth✅ Interactive slicers (Segment, Region, Category, etc.)✅ Drill-down visuals (Top 10 Products, Sub-categories)✅ Dynamic tooltips and conditional formatting✅ Global slicer control and page navigation buttons✅ Optimized SQL queries to support dashboard

❓ Questions Answered

💰 What is the total Sales and Profit across the Superstore?

📊 Which Segments, Regions, and Categories are performing the best?

📦 Which Categories generate the highest Revenue and Profit?

💼 Which Sub-Categories and Products are the top performers by Sales and Profit?

♻️ Are there Sub-Categories with high Sales but low Profitability?

🌍 How do Categories and Sub-Categories perform across different Regions and Segments?

🗓️ Which Years or Months see the highest Sales and Profits?

🚚 What is the average time taken to ship an order, and how does it vary by Region and Ship Mode?

💸 How do different Discount Ranges affect Profitability?

📉 Which Categories or Discounts lead to the lowest Profit Margins or Losses?

🧾 Who are the top Customers based on Sales and Profit?

🌐 Which States and Cities generate the most Revenue and Profit?

🚛 Which Shipping Modes are most commonly used, and how do they impact delivery times and performance?

🔝 What are the Top 10 Sub-Categories and Products based on Sales and Profit?

📈 How has Sales and Profit trended over the Years and Months?

🛠️ Tech Stack

Tool

Purpose

🐬 MySQL

Data import, cleaning, and SQL query generation

📊 Power BI

Dashboard creation, DAX, and visual analytics

📁 Excel

Data transformation and verification

📝 DAX

Calculated fields and KPIs

📂 Key Calculated Columns / Measures

Name

Formula / Logic

Order Year

=YEAR([Order Date])

Month Name

=TEXT([Order Date],"mmmm")

Shipping Delay (Days)

=DATEDIFF(Order Date, Ship Date, DAY)

AOV

SUM(Sales) / COUNT(DISTINCT Order ID)

Profit Margin %

SUM(Profit) / SUM(Sales)

Sales After Discount

Sales * (1 - Discount)

📸 Dashboard Preview
<img width="2879" height="1486" alt="Screenshot 2025-07-23 013539" src="https://github.com/user-attachments/assets/76a70b4c-db32-4b2b-88fd-8bba79b1d94b" />

<img width="2880" height="1486" alt="image" src="https://github.com/user-attachments/assets/24231b86-60fa-44dc-9b41-bfe1f303303e" />


🧠 Learnings

Advanced DAX and time intelligence in Power BI

SQL joins, window functions, and KPI aggregation

Visual storytelling for business insight

Page navigation, bookmark controls, and global slicer syncing

📬 Feedback & Contact

Feel free to raise issues, contribute, or connect with me:

📧 gulshankumar02985@gmail.com

🔗 https://www.linkedin.com/in/gulshankumar01/

📜 License

This project is open-source and free to use for learning and portfolio purposes.

