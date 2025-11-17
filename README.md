# Customers-shopping-behavior-data-analysis.....python-sql-powerbi

# 🛍️ Customer Shopping Behavior Analysis

This project analyzes customer shopping patterns using **Python (EDA)**, **SQL (SQL business analysis)**, and **Power BI** for visualization.  
The insights help businesses understand trends in spending, product preferences, subscription behavior, and customer segmentation.

---

## 📌 1. Project Overview

The dataset consists of **3,900 customer transactions** across multiple product categories.  
This project aims to uncover business insights such as:

- Which groups spend the most?
- How do discounts influence customer behavior?
- Which products perform best?
- Are subscribers more valuable than non-subscribers?

The workflow includes:

1. Data Cleaning & EDA using Python  
2. SQL-based Business Analysis  
3. Power BI Interactive Dashboard  

---

## 📊 2. Dataset Summary

| Feature Type | Details |
|-------------|---------|
| **Rows** | 3,900 |
| **Columns** | 18 |
| **Demographics** | Age, Gender, Location, Subscription Status |
| **Purchases** | Item Purchased, Category, Amount, Season, Size, Color |
| **Behavior** | Discount Applied, Promo Code, Review Rating, Shipping Type |
| **Missing Data** | 37 missing values in Review Rating |

## Dataset used 

<a href="https://github.com/Kiranbr01/Customers-shopping-behavior-data-analysis.....python-sql-powerbi/blob/main/customer_shopping_behavior.csv">DATASET</a>
---

## 🧹 3. Exploratory Data Analysis (Python)

### ✔ Data Cleaning & Preparation
- Imported dataset using **pandas**
- Checked structure with `df.info()` and summary with `df.describe()`
- Filled missing values in **Review Rating** using median rating per category
- Standardized column names to snake_case
- Feature engineering:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant column: `promo_code_used`
- Loaded cleaned DataFrame into **PostgreSQL**

## Dashboard 
<img width="1341" height="728" alt="Screenshot 2025-11-17 153356" src="https://github.com/user-attachments/assets/1fb57d74-bd79-4756-9992-969cd434bc8c" />


---

## 🗄️ 4. Data Analysis Using SQL

The cleaned data was analyzed using **PostgreSQL**.

### Key SQL Insights:
- **Revenue by Gender**
- **High-Spending Discount Users**
- **Top 5 Products by Review Rating**
- **Standard vs Express Shipping Spend**
- **Subscribers vs Non-Subscribers Revenue**
- **Discount-Dependent Products**
- **Customer Segmentation (New, Returning, Loyal)**
- **Top 3 Products per Category**
- **Repeat Buyers & Subscription Probability**
- **Revenue by Age Group**

These SQL queries help identify patterns in spending behavior and customer loyalty.

---

## 📈 5. Power BI Dashboard

A Power BI dashboard was created to visualize:

- Revenue by demographic groups  
- Top products by sales and ratings  
- Purchasing patterns  
- Subscription vs non-subscription behavior  
- Shipping type trends  
- Discount impact  
- Review rating distribution  

---

## 💡 6. Business Recommendations

- **Boost Subscription Enrollment:** Offer exclusive benefits  
- **Enhance Loyalty Programs:** Encourage repeat buying  
- **Optimize Discount Strategy:** Reduce overdependency  
- **Highlight Top Products:** Use them in marketing campaigns  
- **Target High-Value Segments:** Express shipping users, high-spending age groups  

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Data cleaning, EDA |
| PostgreSQL | Business queries & insights |
| Power BI | Visualization |
| Jupyter Notebook | Analysis workflow |

---

## ▶️ How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git


