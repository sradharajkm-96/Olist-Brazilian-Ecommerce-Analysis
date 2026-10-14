# 🛒 Olist Brazilian E-Commerce Data Analysis

### Sales Performance | Customer Behaviour | Product Analysis | Delivery Insights

## 📌 Project Overview

This project analyses the Brazilian E-Commerce Public Dataset by Olist
to understand e-commerce sales performance, product category trends,
payment patterns, customer reviews, and delivery performance.

The project follows a data analytics workflow using Python, Pandas,
NumPy, Matplotlib, and Seaborn.

The analysis includes data cleaning, table integration using joins,
feature engineering, exploratory data analysis (EDA), and visualisation.

## 🎯 Project Objectives

- Clean and prepare the original datasets.
- Integrate related tables using appropriate joins.
- Handle missing values and duplicate records.
- Identify and treat outliers where appropriate.
- Create meaningful derived features.
- Analyse product category performance.
- Explore payment value distributions.
- Examine customer review scores.
- Analyse delivery duration and delivery delays.
- Present findings using clear visualisations.

## 📂 Dataset Description

Dataset: Brazilian E-Commerce Public Dataset by Olist

Source:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset includes information about:

- Orders
- Customers
- Order items
- Products
- Sellers
- Payments
- Reviews
- Geolocation
- Product category translations

## 🛠 Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data cleaning and transformation |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Jupyter Notebook | Analysis and documentation |
| GitHub | Project version control and sharing |

## 🔄 Project Workflow

1. Data loading and initial inspection
2. Data cleaning and preprocessing
3. Data integration using joins
4. Missing-value and duplicate checks
5. Outlier detection and handling
6. Feature engineering
7. Exploratory Data Analysis
8. Data visualisation
9. Interpretation of findings
10. Documentation and reporting

## 🧹 Data Cleaning

The data preparation process includes:

- Inspecting dataset dimensions and data types.
- Checking missing values.
- Checking duplicate records.
- Converting date columns to appropriate formats.
- Merging related tables using common identifiers.
- Checking the quality of the merged dataset.
- Investigating outliers and documenting their treatment.

## ⚙️ Feature Engineering

Derived features used in the analysis include:

- Item Revenue
- Purchase Year
- Purchase Month
- Purchase Month-Year
- Delivery Duration
- Delivery Delay

These features support the analysis of sales trends,
product performance, and delivery efficiency.

## 📊 Exploratory Data Analysis

The EDA examines:

- Product category order counts
- Revenue by product category
- Payment value distribution
- Delivery duration and delivery delay
- Average review scores by product category
- Average product prices by category

## 💡 Key Findings

- Bed, Bath & Table is a leading category by order count
  among the categories analysed.
- Revenue comparisons help identify important product categories.
- Payment values are right-skewed, with many observations
  concentrated at lower values.
- Delivery delay analysis helps compare actual delivery dates
  with estimated delivery dates.
- Review-score comparisons reveal differences across categories.

These findings should be interpreted alongside the charts
and numerical results in the Jupyter Notebook.

## 📁 Project Structure

```text
Olist-Brazilian-Ecommerce-Analysis/
├── README.md
├── data/
│   ├── raw/
│   └── cleaned/
├── notebooks/
│   └── olist_brazilian_e_commerce_data_analysis.ipynb
└── visualizations/



👩‍💻 Author
Sradha Raj
