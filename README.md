# 📊 Vrinda Store Annual Report Dashboard (2022)

An interactive sales analytics dashboard built for **Vrinda Store**, analyzing a **31,000+ row retail transaction dataset** to uncover trends in sales, orders, customer demographics, and channel performance. Built using excel AND power query



---

## 🚀 Overview

This project transforms raw, messy e-commerce sales data into a clean, decision-ready dashboard — the kind of report a business stakeholder could actually use to track performance and spot trends at a glance.

**Key metrics tracked:**
- 💰 Total Sales: ₹21.20M (↑15.55% YoY)
- 🛒 Total Orders: 31,047 (↑14.43% YoY)
- 📈 Average Order Value: ₹684 (↑1.03% YoY)
- 🔄 Return Rate: 5.03% (↑0.42% YoY)

---

## 🔍 Features

- **Dynamic Filters** — Slice data by Month, Sales Channel, and Category
- **Orders vs Sales Trend** — Combined bar + line chart tracking monthly order count against revenue
- **Gender-wise Sales Split** — Men vs Women contribution to total sales
- **Order Status Breakdown** — Delivered, Cancelled, Returned, Refunded (donut chart)
- **Channel-wise Orders** — Performance across Amazon, Flipkart, Myntra, Meesho, Ajio, Nalli & others
- **Age vs Gender Analysis** — Order distribution across Adult, Senior, and Teenager segments
- **Top 5 States by Sales** — Geographic sales concentration (Maharashtra, Karnataka, UP, Telangana, Tamil Nadu)

---

## 🛠️ Tech Stack

| Layer | Tools Used |
|---|---|
| Data Cleaning & Aggregation | power query |
| Dataset Size | ~31,000 rows (raw retail transactions) |


## 📌 Key Insights

- Women accounted for **64% of total sales**, nearly double that of men.
- **92% of orders were successfully delivered**, with cancellations, returns, and refunds together making up only 8%.
- **Amazon (35.5%)** and **Flipkart (21.6%)** were the top two sales channels by volume.
- **Adults (34.59% women, 15.50% men)** were the most active buyer segment, followed by teenagers.
- **Maharashtra and Karnataka** led state-wise sales, together contributing over ₹5.6M.
- Sales peaked around **March**, followed by a gradual decline through the year-end.

---



## 📈 Data Pipeline

1. **Raw data ingestion** — ~31K transaction-level records
2. **Cleaning** — handled missing values, duplicate orders, inconsistent category/channel labels
3. **Aggregation** — grouped by month, gender, age group, state, and channel
4. **Export** — cleaned dataset fed into Chart.js visualizations on the frontend

---

## 👤 Author

**Keshav Dixit**
B.Tech CSE | Aspiring Data Analyst
🔗 [GitHub](https://github.com/Keshavdi19)

---

⭐ If you found this project useful, consider giving it a star!
