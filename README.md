E-Commerce Sales & Customer Analytics System

A Python and SQL-based data analytics project that processes e-commerce transaction data, stores it in SQLite, and generates insights into sales, customers, products, regions, and revenue trends.

Project Overview

This project demonstrates a simple end-to-end data analytics workflow:

Transaction Data
      ↓
Python + Pandas
      ↓
Data Cleaning & Transformation
      ↓
SQLite Database
      ↓
SQL Analytics
      ↓
Business Insights & Visualizations


The project was developed in Jupyter Notebook using Python, Pandas, SQLite, SQL, and Matplotlib.

Technologies Used

Python

Pandas

SQL

SQLite

Matplotlib

Jupyter Notebook

Dataset

The project uses a sample e-commerce dataset containing:

20 transaction records

5 customers

5 products

2 product categories

4 regions

Transaction dates

Product quantities

Unit prices

Customer information

Revenue is calculated using:

Revenue = Quantity × Unit Price

Key Features
Data Processing

Data type validation

Missing-value checking

Duplicate removal

Date conversion

Numeric data validation

Revenue calculation

Monthly data extraction

SQL Analytics

Implemented SQL queries for:

Total revenue

Product-wise sales

Category-wise sales

Region-wise performance

Customer spending

Top customers

Monthly revenue

Above-average orders

Customer ranking

Common Table Expressions (CTEs)

SQL JOIN operations

Window functions

Database Design

The SQLite database contains two tables:

ecommerce.db

├── sales
└── customers


The sales table contains transaction-level information, while the customers table stores customer-related information.

The two tables are combined using SQL JOIN operations.

Visualizations

The project includes Matplotlib visualizations for:

Revenue by product

Monthly revenue trends

Customer spending

Project Structure
ecommerce-sales-customer-analytics/
│
├── Ecommerce_Sales_Customer_Analytics.ipynb
├── ecommerce.db
└── README.md

How to Run

Clone or download this repository.

Open Ecommerce_Sales_Customer_Analytics.ipynb using Jupyter Notebook or JupyterLab.

Install the required libraries if necessary:

pip install pandas matplotlib


Run the notebook cells sequentially.

The SQLite database is created and populated during execution.

Learning Outcomes

Through this project, I practiced:

Python-based data processing

Pandas data manipulation

SQL querying

Relational database concepts

SQLite database operations

JOINs and aggregations

CTEs and window functions

Data validation

Data visualization

Basic end-to-end analytics workflows

Future Improvements

Connect the pipeline to a larger real-world dataset

Add automated data ingestion

Build an interactive dashboard

Add additional customer segmentation

Deploy the analytics pipeline using a cloud platform
