# E-commerce-Data-Warehouse
📌 Project Overview

This project focuses on building a Data Warehouse (DW) and ETL pipelines for an E-Commerce business using Informatica PowerCenter and Oracle Database. The primary goal is to process raw flat file data (CSV), transform it, and load it into a structured Data Warehouse to answer key business questions related to customer behavior, order processing, logistics, and payments.

🎯 Business Needs Addressed

The Data Warehouse helps answer critical business questions, including:

✅ Peak seasons and user order trends.

✅ Preferred payment methods and installment patterns.

✅ Customer spending time and purchase frequency per state.

✅ Logistics routes with heavy traffic and delivery delays.

✅ Impact of late deliveries on customer satisfaction.

🛠️ Tech Stack & Tools Used
ETL Tool: Informatica PowerCenter

Database: Oracle

Programming: SQL, PL/SQL

Data Modeling: Dimensional Modeling (snowflake Schema)

Version Control: Git & GitHub

🗂️ Project Architecture

📌 Staging Layer
Defined DDL for 7 flat files (CSV) in Oracle.

Extracted data from CSV files and loaded it into staging tables.

📌 Data Warehouse Layer

Designed a dimensional model to ensure efficient reporting.

Implemented Fact & Dimension Tables to support analytics.

Applied Slowly Changing Dimensions (SCD):

SCD Type 1: Dim_Feedback, Dim_Products, Fct_Order

SCD Type 2: Dim_User, Dim_Payment, Dim_Order_Item

SCD Type 3: Dim_Seller

📌 ETL Process

Full Load & Incremental Load versions implemented.

Applied data transformation & cleansing in Informatica.

Used Lookup, Router, Aggregator, and Update Strategy transformations.

📊 Reports & Insights Generated

Order trends & peak season detection

Customer behavior analysis

Payment methods & installment preferences

Delivery delays & logistics route optimization

