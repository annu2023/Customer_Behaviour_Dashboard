# Customer_Behaviour_Dashboard
This project presents an interactive Customer Behaviour Dashboard built using Power BI to analyze customer purchasing patterns, engagement trends, and business performance metrics.
📊 Customer Behaviour Analytics Dashboard

PostgreSQL | Python | Power BI

🏢 Business Problem

A leading retail company wants to better understand its customer shopping behavior to improve sales, customer satisfaction, and long-term loyalty.

The management team has observed changing purchasing patterns across:

Customer demographics

Product categories

Sales channels (Online vs Offline)

They are particularly interested in identifying which factors — such as discounts, reviews, seasons, and payment preferences — influence consumer decisions and repeat purchases.

🎯 Overarching Business Question

How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?

🔎 Project Overview

This project builds an end-to-end analytics solution to answer the above business question using structured consumer data.

The solution integrates:

PostgreSQL for data storage and relational modeling

Python (Pandas) for data cleaning and exploratory analysis

Power BI for interactive dashboard visualization

The final dashboard provides actionable insights into customer behavior, revenue trends, and marketing optimization opportunities.

🗂️ Dataset Files

customers.csv – Customer demographic information

orders.csv – Transactional purchase data

products.csv – Product category and pricing details

Customer Behaviour Dashboard.pbix – Interactive Power BI dashboard

⚙️ Tech Stack

PostgreSQL – Database design, SQL queries, joins, aggregations

Python (Pandas, SQLAlchemy, Psycopg2) – Data preprocessing & EDA

Power BI – Data modeling, DAX calculations, dashboard development

🔄 Project Workflow
1️⃣ Data Preparation

Imported CSV files into PostgreSQL

Cleaned missing values and standardized formats using Python

Built relational schema connecting customers, orders, and products

2️⃣ Data Analysis

Used SQL (JOINs, CTEs, GROUP BY, Window Functions) to analyze trends

Performed customer segmentation and behavioral analysis

Evaluated discount impact and repeat purchase behavior

3️⃣ Dashboard Development

Created interactive Power BI reports including:

KPI Cards (Total Revenue, Orders, Customers, AOV)

Online vs Offline Sales Comparison

Category-wise Revenue Distribution

Seasonal Sales Trends

Payment Method Preferences

Customer Retention Insights

📊 Key Insights Generated

Identification of high-value customer segments

Seasonal trends influencing purchasing behavior

Impact of discounts and reviews on sales

Channel performance comparison (Online vs Offline)

Customer repeat purchase patterns

💡 Business Value

This project demonstrates how consumer shopping data can be leveraged to:

Improve targeted marketing campaigns

Optimize pricing and discount strategies

Enhance customer engagement

Support inventory and seasonal planning

Increase long-term customer loyalty

🚀 How to Run

Import CSV files into PostgreSQL

Run Python scripts for cleaning and transformation

Connect Power BI to PostgreSQL

Open Customer Behaviour Dashboard.pbix

Refresh data and explore insights

🔮 Future Enhancements

RFM Analysis

Customer Churn Prediction Model

Cohort Analysis

Deployment to Power BI Service
