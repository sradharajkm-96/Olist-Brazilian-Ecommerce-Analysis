# Brazilian E-Commerce Sales and Customer Analysis

## Project Overview

This project analyses the Brazilian E-Commerce Public Dataset provided by Olist.

The dataset contains information about orders, customers, products, sellers, payments, reviews and geolocation.

The project focuses on data cleaning, preprocessing, data integration and feature engineering using Python.

## Problem Statement

The Olist dataset is distributed across multiple related tables. The objective of this project is to clean and integrate the datasets using appropriate join operations and prepare the data for further analysis.

## Dataset Source

Brazilian E-Commerce Public Dataset by Olist

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset Tables

The dataset contains information from the following tables:

- Orders
- Customers
- Order Items
- Products
- Sellers
- Payments
- Reviews
- Product Category Translation
- Geolocation

## Project Work Completed

### Data Loading
- Loaded the Olist datasets using Pandas.
- Inspected the structure and dimensions of the datasets.

### Data Cleaning
- Checked missing values.
- Checked duplicate records.
- Converted date columns into appropriate datetime format.

### Data Integration
The related datasets were integrated using LEFT JOIN operations.
The main tables were merged using common keys such as:

- order_id
- customer_id
- product_id
- seller_id

Main relationships include:

- Orders + Customers
- Orders + Order Items
- Order Items + Products
- Order Items + Sellers
- Products + Category Translation
- Orders + Payment Summary
- Orders + Review Summary
- Customer/Seller location + Geolocation

The final master dataset was prepared for further analysis.

### Feature Engineering

Derived features were created for:

- Item Revenue
- Purchase Year
- Purchase Month
- Delivery Duration
- Delivery Delay

  ## Project Work Completed

- Data cleaning and preprocessing
- Merging related datasets using joins
- Handling missing values and duplicate records
- Outlier detection and handling in the merged dataset
- Feature engineering and derived columns
- Exploratory Data Analysis (EDA)
- Data visualization using Matplotlib and Seaborn
- Analysis of product categories, revenue, payments, reviews, and delivery performance

## Current Status

Data cleaning, feature engineering, EDA, and visualizations have been completed using Python in Jupyter Notebook.

## Future Work

- Present key business insights and recommendations



## Author

Sradha Raj
