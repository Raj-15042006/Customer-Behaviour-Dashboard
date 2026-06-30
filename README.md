# Customer Shopping Behavior Analytics Dashboard

## Project Overview

The **Customer Shopping Behavior Analytics Dashboard** is an end-to-end data analytics project designed to transform raw retail transaction data into meaningful business intelligence. The project explores purchasing patterns, customer demographics, shopping preferences, and revenue drivers to help retailers make informed, data-driven decisions.

The complete workflow includes **Python** for data preprocessing, **PostgreSQL** for analytical querying, and **Power BI** for creating an interactive business dashboard.

---

# Dataset Overview

| Attribute      | Details                           |
| -------------- | --------------------------------- |
| Total Records  | **5,050 Customer Transactions**   |
| Total Features | **17 Columns**                    |
| Dataset Type   | Retail Customer Shopping Behavior |
| Tools Used     | Python, PostgreSQL, Power BI      |

### Dataset Includes

### Customer Information

* Customer ID
* Age
* Gender
* Location
* Subscription Status

### Purchase Information

* Item Purchased
* Product Category
* Purchase Amount (USD)
* Previous Purchases
* Frequency of Purchases

### Shopping Preferences

* Size
* Color
* Season
* Shipping Type
* Payment Method
* Discount Applied
* Review Rating

---

# Data Cleaning & Preprocessing (Python)

The dataset was cleaned and prepared before analysis to ensure consistency and accuracy.

### Data Preparation Steps

* Imported the dataset using **Pandas**
* Examined data structure using `.info()` and `.describe()`
* Identified and handled missing values
* Imputed missing **Review Rating** values using the median rating
* Standardized column names into a consistent naming convention
* Converted categorical fields into analysis-friendly formats
* Created derived features including:

  * Age Groups
  * Purchase Frequency Categories
* Checked for duplicate records
* Validated data types and corrected inconsistencies
* Exported the cleaned dataset into **PostgreSQL** for SQL-based analysis

---

# Exploratory Data Analysis (EDA)

Exploratory analysis was performed to understand customer behavior and identify important trends.

The analysis focused on:

* Customer age distribution
* Gender-wise shopping behavior
* Revenue distribution across product categories
* Seasonal purchasing trends
* Discount usage patterns
* Subscription behaviour
* Payment method preferences
* Shipping preferences
* Product review analysis
* Purchase frequency patterns

---

# SQL Business Analysis

Business-focused SQL queries were written to answer real-world retail questions.

### Key Analyses Performed

1. Revenue comparison between male and female customers
2. Average purchase value by product category
3. Highest revenue-generating categories
4. Top-rated products based on customer reviews
5. Spending behavior of subscribed vs non-subsscribed customers
6. Impact of discounts on customer spending
7. Customer segmentation into New, Returning, and Loyal customers
8. Most frequently purchased products within each category
9. Relationship between previous purchases and subscription status
10. Revenue contribution across different age groups
11. Preferred payment methods
12. Shopping behaviour across seasons
13. Shipping type preference analysis

---

# Power BI Dashboard

An interactive Power BI dashboard was developed to provide business stakeholders with a visual overview of customer shopping behaviour.

### Dashboard Highlights

* Total Revenue
* Total Customers
* Average Purchase Value
* Customer Segmentation
* Revenue by Category
* Revenue by Gender
* Revenue by Age Group
* Subscription Analysis
* Purchase Frequency Analysis
* Seasonal Sales Trends
* Shipping Type Distribution
* Payment Method Analysis
* Product Performance Dashboard
* Interactive Filters and Drill-down Capabilities

---

# Key Business Insights

The analysis revealed several actionable insights:

* Subscribers consistently generated higher revenue than non-subscribers.
* Loyal customers accounted for a significant share of overall sales.
* Strategic discounts encouraged purchases without substantially reducing total revenue.
* Certain product categories consistently outperformed others in both sales and customer ratings.
* Purchase frequency showed a strong relationship with customer lifetime value.
* Seasonal demand varied across categories, highlighting opportunities for targeted promotional campaigns.

---

# Business Recommendations

Based on the analysis, the following recommendations are proposed:

* Introduce enhanced subscription benefits to improve customer retention.
* Develop loyalty reward programs for repeat customers.
* Apply discounts strategically to maximise revenue while protecting profit margins.
* Increase promotion of top-performing and highly rated products.
* Personalise marketing campaigns based on customer demographics and purchase history.
* Optimise inventory planning using seasonal purchasing trends.

---

# Technology Stack

| Technology      | Purpose                                       |
| --------------- | --------------------------------------------- |
| Python (Pandas) | Data Cleaning & Preprocessing                 |
| PostgreSQL      | Data Storage & SQL Analytics                  |
| Power BI        | Interactive Dashboard & Business Intelligence |

---

# Project Workflow

1. Collect the raw customer shopping dataset.
2. Clean and preprocess the data using Python.
3. Load the processed dataset into PostgreSQL.
4. Perform business-oriented SQL analysis.
5. Build an interactive Power BI dashboard.
6. Generate business insights and recommendations.

---

# Project Outcome

This project demonstrates the complete lifecycle of a modern data analytics solution—from raw data preparation to business reporting. It showcases practical skills in data cleaning, SQL querying, dashboard development, and insight generation, making it a strong portfolio project for Business Intelligence and Data Analytics roles.
