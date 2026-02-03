# Customer_Behaviour_Analysis

Overview

This project analyzes customer shopping behavior to uncover trends in purchasing patterns, customer segments, and product performance. The goal is to demonstrate an end-to-end data analytics workflow — from raw data processing to business insights and visualization.

The project combines Python, SQL, Power BI, and reporting tools to simulate how a real business would use data to support decision-making.

Dataset

The dataset contains customer transaction records, including:

Customer demographics (age, gender, subscription status)

Purchase information (product category, purchase amount, shipping type)

Behavioral indicators (reviews, discounts, purchase frequency)

After cleaning, the dataset was structured for both exploratory analysis and database querying.

Tools & Technologies
Tool	Purpose
Python (Pandas, NumPy, Matplotlib/Seaborn) -	Data cleaning, transformation, and EDA
PostgreSQL - Structured querying and business analysis
SQL	Customer segmentation and revenue analysis
Power BI	Interactive dashboard creation
Jupyter Notebook	Analysis workflow and documentation

Project Steps
1. Data Loading & Exploration (Python)

Loaded dataset using Pandas

Reviewed structure, data types, and summary statistics

Identified missing and inconsistent values

2. Data Cleaning & Preparation

Handled missing values in review ratings

Standardized column names for consistency

Created new features such as age groups and purchase frequency

Removed redundant columns

Exported cleaned data to SQL database

3. SQL Business Analysis

Used SQL to answer business-focused questions such as:

Revenue comparison by gender

Subscriber vs non-subscriber spending behavior

Top-performing product categories

Impact of shipping type on purchase value

Customer segmentation (New vs Returning vs Loyal)

Revenue contribution by age group

4. Power BI Dashboard

An interactive dashboard was built to visualize:

Total customers, average purchase value, and average rating

Revenue and sales by product category

Customer distribution by subscription status

Revenue and sales by age group

Filters for gender, category, subscription status, and shipping type

5. Reporting & Presentation

A structured project report was created summarizing insights and recommendations


Dashboard Highlights

The Power BI dashboard helps stakeholders quickly understand:

Which customer segments generate the most revenue

Which product categories drive the highest sales

How subscription status impacts purchasing behavior

Age groups with the strongest buying patterns

Key Results

Subscribers showed higher average spending compared to non-subscribers

Clothing and Accessories generated the highest revenue

Young Adult and Middle-Aged customers contributed the most to overall sales

Express shipping users tended to have higher purchase amounts

Repeat customers were more likely to subscribe, indicating strong loyalty potential

How to Run This Project

1. Python Analysis

Clone the repository

Install required libraries:

pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2


Open the Jupyter Notebook and run all cells to:

Clean data

Generate features

Export data to SQL

2. SQL Analysis

Import the cleaned dataset into PostgreSQL/MySQL

Run the SQL scripts in the /sql folder to reproduce business queries

3. Power BI Dashboard

Open the .pbix file in Power BI Desktop

Refresh the data connection if needed

Interact with filters and visuals

Business Value

This project demonstrates how data can be used to:

Improve customer targeting

Identify high-value segments

Optimize promotional strategies

Support data-driven product and marketing decisions

Author

Ashwathi
Aspiring Data Analyst | Python • SQL • Power BI
