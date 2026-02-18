# Customer_Behaviour_Dashboard
This project presents an interactive Customer Behaviour Dashboard built using Power BI to analyze customer purchasing patterns, engagement trends, and business performance metrics.
📊 Customer Behaviour Analytics Dashboard

PostgreSQL | Python | Power BI

🔎 Project Overview

This project analyzes customer purchasing behavior using PostgreSQL for data storage, Python for data processing, and Power BI for interactive visualization.

The goal is to extract meaningful business insights from raw transactional data and build a dynamic dashboard that helps in understanding customer trends, product performance, and revenue growth.

🗂️ Dataset Files

The project includes the following datasets:

customers.csv – Customer demographic and profile information

orders.csv – Transactional order details

products.csv – Product category and pricing information

Customer Behaviour Dashboard.pbix – Final interactive Power BI dashboard

⚙️ Tech Stack

PostgreSQL – Database creation, data storage, SQL queries

Python (Pandas, SQLAlchemy, Psycopg2) –

Data cleaning & transformation

Data loading into PostgreSQL

Exploratory Data Analysis (EDA)

Power BI – Data modeling, DAX measures, dashboard development

🔄 Project Workflow

Data Collection

Imported CSV files into PostgreSQL database

Data Cleaning & Transformation (Python)

Handled missing values

Standardized data formats

Removed duplicates

Performed feature engineering

Data Modeling (PostgreSQL)

Created relational schema

Used JOIN operations to combine customers, orders, and products

Aggregated sales and revenue metrics

Visualization (Power BI)

Built KPIs: Total Revenue, Total Orders, Average Order Value

Customer segmentation analysis

Product category performance

Time-based sales trends

Interactive slicers and filters

📊 Key Insights

Identification of high-value customers

Revenue contribution by product category

Repeat vs one-time purchase behavior

Seasonal sales patterns

Customer purchasing frequency trends

🧠 SQL Concepts Used

INNER JOIN

GROUP BY & HAVING

Aggregate Functions (SUM, COUNT, AVG)

Window Functions

CTEs (Common Table Expressions)

📈 Dashboard Features

KPI Cards (Revenue, Orders, Customers)

Monthly/Quarterly Sales Trend

Category-wise Revenue Distribution

Top Customers Analysis

Dynamic filtering by date & category

🚀 How to Run the Project

Import CSV files into PostgreSQL

Run Python scripts to clean and load data

Connect Power BI to PostgreSQL

Open Customer Behaviour Dashboard.pbix

Refresh the data model

🔮 Future Enhancements

Customer churn prediction model

RFM analysis

Cohort analysis

Deployment using Power BI Service
