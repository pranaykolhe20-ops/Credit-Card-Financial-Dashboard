📊 Credit Card Financial Dashboard – Power BI
📌 Project Overview

This project presents a Credit Card Weekly Financial Dashboard built using Power BI, SQL, and DAX. The dashboard provides insights into credit card transactions, customer behavior, and financial performance metrics.

The goal of this project is to analyze credit card operations and visualize key business metrics through an interactive dashboard to help stakeholders make data-driven decisions.

🎯 Project Objective

The objective of this project is to develop a comprehensive credit card weekly dashboard that provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations effectively.

🛠️ Technologies Used

Power BI – Data visualization & dashboard creation

SQL – Data storage and querying

DAX (Data Analysis Expressions) – Calculations and measures

CSV Dataset – Source data

⚙️ Project Workflow
1️⃣ Data Collection

Dataset downloaded from GitHub

Data stored in CSV format

Imported into SQL database

2️⃣ Data Preparation

Created SQL tables

Imported CSV data into SQL

Cleaned and structured the dataset

3️⃣ Data Modeling

Connected SQL database to Power BI

Created table relationships

Built data model

4️⃣ Data Analysis Using DAX

Several calculated columns and measures were created.

Example DAX Calculation
AgeGroup =
SWITCH(
 TRUE(),
 'public cust_detail'[customer_age] < 30, "20-30",
 'public cust_detail'[customer_age] >= 30 && 'public cust_detail'[customer_age] < 40, "30-40",
 'public cust_detail'[customer_age] >= 40 && 'public cust_detail'[customer_age] < 50, "40-50",
 'public cust_detail'[customer_age] >= 50 && 'public cust_detail'[customer_age] < 60, "50-60",
 'public cust_detail'[customer_age] >= 60, "60+",
 "unknown"
)

Other important calculations include:

Income group segmentation

Weekly revenue analysis

Current vs previous week revenue comparison

These calculations help analyze customer demographics and financial performance.

📊 Dashboard Features

The dashboard provides insights into:

Revenue Analysis

Weekly Transaction Trends

Customer Segmentation

Credit Card Type Performance

State-wise Revenue Distribution

Transaction Amount & Count Analysis

Activation Rate Monitoring

Delinquency Rate Tracking

📈 Key Business Insights
Weekly Performance

Revenue increased by 28.8% week-over-week

Transaction amount and count increased

Customer count increased

Year-To-Date Overview

Total Revenue: 57M

Total Interest Earned: 8M

Total Transaction Amount: 46M

Customer insights:

Male customers contributed 31M revenue

Female customers contributed 26M revenue

Credit card insights:

Blue & Silver credit cards contribute 93% of transactions

Regional insights:

Texas, New York, and California contribute 68% of revenue

Performance metrics:

Activation Rate: 57.5%

Delinquent Rate: 6.06%
