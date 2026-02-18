# 📊 Customer Sales Analytics Dashboard

## 📌 Project Overview

This project analyzes customer shopping behavior using Power BI.  
The goal of this dashboard is to identify revenue patterns, customer segments, and category performance to support business decision-making.

---

## 📂 Tools Used

- Power BI
- DAX
- Excel / CSV Dataset
- Data Modeling

---

## 📊 Dashboard Features

- KPI Cards (Total Revenue, Average Purchase)
- Revenue by Category
- Revenue by Gender
- Revenue by Subscription Status
- Revenue by Payment Method
- Interactive Filters (Category, Gender)

---

## 📁 Dataset Information

The dataset contains customer shopping behavior data including:

- Customer ID
- Age
- Gender
- Category
- Purchase Amount (USD)
- Subscription Status
- Payment Method
- Review Rating
- Previous Purchases

---

## 📈 Key Business Insights

- Clothing category generates the highest revenue.
- Non-subscribers contribute more revenue than subscribers.
- Male customers generate a higher portion of total revenue.
- Credit Card and PayPal are the most used payment methods.
- 
## 🖼 Dashboard Preview
![Dashboard Overview](<img width="1920" height="1080" alt="dashboard_overview png" src="https://github.com/user-attachments/assets/c3a2e215-e905-459e-8329-5ba743fc7d79" />
)

---

## 📌 DAX Measures Used

```DAX
Total Revenue = SUM('shopping_behavior'[Purchase Amount (USD)])

Average Purchase = AVERAGE('shopping_behavior'[Purchase Amount (USD)])
