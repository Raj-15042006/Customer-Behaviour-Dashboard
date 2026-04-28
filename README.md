# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories. The objective is to uncover patterns in spending, customer segmentation, product preferences, and subscription behavior to support data-driven business decisions.

---

## 📊 Dataset Summary

* **Rows:** 3,900
* **Columns:** 18
* **Key Features:**

  * **Customer Demographics:** Age, Gender, Location, Subscription Status
  * **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color
  * **Shopping Behavior:** Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type
* **Missing Data:** 37 missing values in `Review Rating`

---

## 🧹 Data Preparation & EDA (Python)

Key preprocessing and exploratory steps:

* Loaded dataset using `pandas`
* Performed structural checks with `.info()` and `.describe()`
* Handled missing values:

  * Imputed `Review Rating` using median per category
* Standardized column names (snake_case)
* Feature engineering:

  * `age_group` (binned age ranges)
  * `purchase_frequency_days`
* Removed redundant column (`promo_code_used`)
* Exported cleaned dataset to **PostgreSQL** for further analysis

---

## 🗄️ Data Analysis (SQL)

Business-focused queries executed in PostgreSQL:

1. Revenue comparison by gender
2. High-spending customers using discounts
3. Top 5 highest-rated products
4. Purchase behavior by shipping type
5. Subscribers vs non-subscribers (revenue & spend)
6. Products most dependent on discounts
7. Customer segmentation:

   * New
   * Returning
   * Loyal
8. Top 3 products per category
9. Subscription likelihood among repeat buyers
10. Revenue contribution by age group

---

## 📈 Dashboard (Power BI)

An interactive dashboard was built to visualize:

* Revenue trends
* Customer segments
* Product performance
* Purchase behavior patterns

---

## 💡 Business Recommendations

* **Boost subscriptions:** Offer exclusive perks
* **Loyalty programs:** Incentivize repeat purchases
* **Optimize discounts:** Balance revenue vs margins
* **Promote top products:** Highlight best-rated and best-selling items
* **Target marketing:** Focus on high-value customer segments

---

## 🛠️ Tech Stack

* **Python** (Pandas, Data Cleaning, EDA)
* **PostgreSQL** (SQL Analysis)
* **Power BI** (Data Visualization)

---

## 🚀 How to Use

1. Clone the repository
2. Run the Python preprocessing script
3. Load cleaned data into PostgreSQL
4. Execute SQL queries for insights
5. Open Power BI dashboard for visualization

---

## 📎 Key Insights

* Subscription status strongly correlates with higher spending
* Discount usage does not always reduce revenue—strategic use matters
* Loyal customers contribute a significant portion of total revenue

---

## 📬 Contact

For questions or collaboration, feel free to reach out.
