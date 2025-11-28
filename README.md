# Customer Shopping Behavior Analysis :

This project analyzes customer shopping behavior using transactional data to uncover patterns in spending, subscription behavior, product preferences, and customer segmentation. 
The objective is to provide data-driven insights to support strategic business decisions in marketing, operations, and customer management.

# Project Overview :

The analysis is based on 3,900 customer transactions.

The workflow includes:

- Python (Pandas) for data cleaning, EDA, and feature engineering.

- MS SQL Server for structured analytical queries.

- Power BI for interactive visualization and reporting.

This end-to-end pipeline provides both deep analytical insights and an intuitive dashboard for decision-makers.

# Technology Stack :

**Python (Pandas):** Data preprocessing, feature engineering

**MS SQL Server:** Business-driven structured queries

**Power BI:** Visual dashboard creation

## Key Insights :

### Revenue and Spending Patterns :

- Male customers generated **$157,890**, while female customers generated **$75,191**.

- Customers using Express Shipping had an average purchase value of **$60**, compared to **$58** for Standard Shipping.

- Customers with **IDs 43, 96, 194, and 205** used a discount but still spent **$100**, exceeding the overall average purchase amount of **$59.76**.

### Customer Segmentation and Subscription :

- Customer distribution: **3,116 Loyal**, **701 Returning**, and **83 New customers**.

- Revenue by subscription status:

- Non-subscribed customers: **$170,436**

- Subscribed customers: **$62,645**

- Average purchase amount for both groups: **$59**

- Among repeat buyers (more than five previous purchases): **2,518** are non-subscribers and **958** are subscribers.

### Product Preferences :

- Highest-rated products by average review score:

- Gloves **(3.86)**

- Sandals **(3.84)**

- Boots **(3.82)**

- Hat **(3.8)**

- Handbag **(3.78)**

- Highest discount usage: **Hat (50%), Sneakers (49.66%), Coat (49.07%)**

  ### Data Preprocessing and Feature Engineering :

- **37** missing values were identified in the Review Rating column and imputed using the median rating by product category.

- The Promocode Used column was removed due to redundancy with Discount Applied.

- Two new features were engineered:

- **Age_Groups** (categorizing customers by age ranges)

- **Purchase_Frequency_Days** (days between purchases)

  ### Dashboard Visualization :

A fully interactive Power BI dashboard displays all insights with filtering options for:

- Gender

- Age_Groups

- Category

- Shipping_Type

This enables dynamic exploration of behavioral and purchasing trends

<img width="1410" height="715" alt="Screenshot 2025-11-27 184452" src="https://github.com/user-attachments/assets/d34dfa94-6a13-4340-a016-08cc3c6eb4be" />
