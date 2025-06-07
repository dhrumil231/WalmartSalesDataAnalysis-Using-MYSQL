🛒 Walmart Sales Data Analysis using MySQL
📌 Project Overview
This project is an end-to-end Sales Data Analysis performed on Walmart transactional data using MySQL as the querying and transformation engine and a CSV file as the data source. The goal is to uncover valuable business insights from raw data by answering strategic questions across different dimensions such as products, sales, customers, and operational performance.

🎯 Project Purpose
Problem Statement:
"How can Walmart improve its operational and sales decisions by analyzing its retail sales data to identify high-performing branches, top product lines, customer behaviors, and peak revenue periods?"

This project aims to:

Understand trends and patterns within the sales data.

Identify key business drivers and areas for improvement.

Provide actionable insights based on descriptive analytics.

📂 Dataset Description
Source: CSV File (Walmart Sales Data)

Total Records: 1000+

Features:

invoice_id, branch, city, customer_type, gender

product_line, unit_price, quantity, VAT, total

date, time, payment_method, cogs, gross_income, rating

Feature Engineering Columns:

time_of_day: Categorized into Morning, Afternoon, Evening

day_name: Weekday extracted from the date

month_name: Month extracted from the date

🛠️ Approach and Steps
Created MySQL Database and Table:

Defined schema using appropriate data types and constraints.

Loaded CSV Data into MySQL:

Ensured integrity of transactional and categorical data.

Performed Feature Engineering:

Added new columns: time_of_day, day_name, month_name

Executed Descriptive Analytics:

Wrote SQL queries to answer key business questions.

Categorized Insights:

Grouped queries and results into thematic business areas.

❓ Business Questions Answered
🧩 Generic Questions
How many unique cities does the data have?

Which branch is located in which city?

How many unique customer types and payment methods exist?

What is the most common customer type and payment method?

📦 Product Analysis
How many unique product lines are there?

What is the most selling product line?

Which product line generates the highest revenue?

Which product line has the highest average VAT?

What is the most common product line by gender?

What is the average rating for each product line?

💰 Sales Analysis
What is the total revenue by month?

Which month had the highest Cost of Goods Sold (COGS)?

Which city/branch generated the most revenue?

Which branch sold more than average quantity?

What is the number of sales during different times of day by weekday?

Which day of the week has the highest average ratings?

Which day has the most sales per branch?

👥 Customer Insights
Which customer type brings in the most revenue?

Which customer type pays the most VAT?

Which customer type buys the most products?

Which gender dominates the customer base?

What is the gender distribution per branch?

Which time of the day and branch receives the best customer ratings?

📈 Key Insights Summary
Branch C records the highest revenue and customer satisfaction ratings.

Food and beverages is the most popular and profitable product line.

Evening sees the highest number of sales across all days.

E-wallets are the most commonly used payment method.

Member customers generate more revenue than normal customers.

Highest average ratings are received on Monday, Tuesday, and Friday.

🧰 Tools & Technologies Used
SQL (MySQL): Querying, feature engineering, and analytics

CSV (Excel): Raw data source

(Optional extensions: Tableau, Power BI, or Python for visualization and automation)

🚀 Future Enhancements
Create interactive dashboards using Tableau or Power BI

Automate data loading and querying using Python

Explore predictive analytics using machine learning models
