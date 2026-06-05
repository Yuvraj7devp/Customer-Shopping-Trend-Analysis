# Customer-Shopping-Trend-Analysis

Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior for a retail company to uncover purchasing patterns, customer preferences, and key drivers of customer loyalty. The goal is to transform raw consumer data into actionable business insights that can improve customer engagement, optimize marketing strategies, and increase overall sales performance.

### Business Problem
A leading retail company wants to better understand its customers' shopping behavior across demographics, product categories, seasons, and sales channels (Online vs Offline). Management seeks to identify factors such as discounts, customer reviews, payment preferences, and seasonal trends that influence purchasing decisions and repeat purchases.

### Business Question

> How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?

---

# 🎯 Project Objectives

* Analyze customer demographics and purchasing patterns.
* Identify high-value customer segments.
* Evaluate customer loyalty and repeat purchase behavior.
* Measure the impact of discounts on purchasing decisions.
* Compare online and offline shopping performance.
* Discover seasonal sales trends.
* Generate actionable business recommendations.
* Build an interactive Power BI dashboard for decision-making.

---

# 🗂️ Dataset Information

The dataset contains customer transaction and shopping behavior information, including:

| Feature             | Description                  |
| ------------------- | ---------------------------- |
| Customer ID         | Unique customer identifier   |
| Age                 | Customer age                 |
| Gender              | Customer gender              |
| Product Category    | Purchased product category   |
| Purchase Amount     | Transaction value            |
| Season              | Season of purchase           |
| Discount Applied    | Whether discount was applied |
| Review Rating       | Customer review score        |
| Previous Purchases  | Number of prior purchases    |
| Payment Method      | Payment type used            |
| Subscription Status | Loyalty program membership   |
| Shopping Channel    | Online or Offline purchase   |

---

# 🛠️ Technology Stack

### Programming & Analysis

* Python
* Pandas

### Database

* PostgreSQL
* SQL

### Visualization

* Power BI

### Version Control

* Git
* GitHub

---

# 📂 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── shopping_behavior.csv
│
├── Python/
│   ├── data_cleaning.ipynb
│   ├── eda_analysis.ipynb
│   └── visualization.ipynb
│
├── SQL/
│   ├── schema.sql
│   ├── business_queries.sql
│   └── customer_analysis.sql
│
├── PowerBI/
│   └── Customer_Shopping_Behavior.pbix
│
├── Presentation/
│   └── Customer_Shopping_Behavior_Analysis.pptx
│
├── Report/
│   └── Project_Report.pdf
│
└── README.md
```

# 🔍 Exploratory Data Analysis (EDA)

The dataset was cleaned, transformed, and analyzed using Python.

### Key Analysis Performed

✔ Data Cleaning

✔ Missing Value Analysis

✔ Duplicate Removal

✔ Data Type Conversion

✔ Feature Engineering

✔ Customer Demographic Analysis

✔ Product Category Analysis

✔ Seasonal Trend Analysis

✔ Discount Impact Analysis

✔ Customer Loyalty Analysis

✔ Payment Method Analysis

### Sample Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

# 🗄️ SQL Business Analysis

The cleaned dataset was structured into relational tables to simulate real-world retail transactions.

### Business Questions Answered

* Which product categories generate the highest revenue?
* Which customer segments contribute most to sales?
* How effective are discounts in driving purchases?
* Which seasons generate the highest revenue?
* Are loyalty program members more valuable?
* What are the preferred payment methods?
* How does online performance compare to offline performance?

### Sample SQL Query

```sql
SELECT
category,
SUM(purchase_amount) AS revenue
FROM customer_transactions
GROUP BY category
ORDER BY revenue DESC;
```

---

# 📊 Power BI Dashboard

An interactive dashboard was developed to provide business stakeholders with real-time insights.

### Dashboard Pages

### Executive Overview

* Total Revenue
* Total Customers
* Average Order Value
* Repeat Purchase Rate

### Customer Insights

* Age Distribution
* Gender Analysis
* Customer Segmentation

### Product Performance

* Revenue by Category
* Top Performing Products

### Sales Trends

* Seasonal Revenue Analysis
* Discount Impact

### Loyalty Analysis

* Repeat Purchase Behavior
* Subscription Status Performance

### Channel Analysis

* Online vs Offline Revenue
* Payment Method Preferences

---

# 💡 Key Insights

### Customer Loyalty Matters

Customers enrolled in subscription programs demonstrate significantly higher repeat purchase rates and spending behavior.

### Discounts Increase Purchase Value

Customers who received discounts showed higher average transaction values than non-discounted customers.

### Seasonal Demand Drives Revenue

Winter and Fall seasons generated the highest sales volumes due to holiday and festive shopping trends.

### Customer Satisfaction Influences Retention

Higher review ratings strongly correlate with increased repeat purchases.

### Digital Payments Dominate

UPI and Credit Cards are the most preferred payment methods, highlighting the growing adoption of digital payment systems.

### Online Shopping Continues to Grow

Online customers exhibit strong purchasing activity and higher engagement compared to traditional channels.

---

# 📈 Business Recommendations

### 1. Expand Loyalty Programs

* Introduce reward points and tier-based memberships.
* Provide personalized offers to loyal customers.

### 2. Optimize Seasonal Marketing

* Focus campaigns around high-performing seasons.
* Launch holiday bundles and festive promotions.

### 3. Implement Personalized Discounts

* Target high-value customers with tailored promotions.
* Use predictive analytics for offer recommendations.

### 4. Improve Customer Experience

* Enhance product quality and delivery speed.
* Strengthen customer support services.

### 5. Focus on Top Categories

* Increase inventory for high-performing categories.
* Implement cross-selling and upselling strategies.

### 6. Promote Digital Payments

* Offer cashback and rewards for digital transactions.
* Simplify checkout experiences.

---

# 📊 Project Outcomes

* Improved understanding of customer behavior.
* Identification of key revenue-generating customer segments.
* Insights into loyalty and retention drivers.
* Data-driven recommendations for business growth.
* Interactive dashboard for executive decision-making.

---

# 🚀 Future Enhancements

* Customer Segmentation using Machine Learning.
* Customer Lifetime Value (CLV) Prediction.
* Recommendation System Development.
* Churn Prediction Modeling.
* Real-time Retail Analytics Dashboard.

---

# 👨‍💻 Author

**Yuvraj Bachhav**

Data Analyst | SQL | Python | Power BI

### Connect With Me

* LinkedIn: [www.linkedin.com/in/yuvrajbachhav24
]
* GitHub: [github.com/Yuvraj7devp]
* Email: [yuvraj7usa@gmail.com]

---

⭐ If you found this project useful, consider giving it a star on GitHub!
