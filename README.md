# Blinkit_360-_Business_-_Operations_Analytics

**Blinkit 360° Business Operations Analytics** | An end-to-end data analytics project using Excel, SQL, Power Bi to analyze customers, orders, products, inventory, delivery performance, marketing, and customer feedback to uncover actionable business insights.


# 🛒 Blinkit Business Performance Analysis | Power BI Dashboard

An end-to-end business intelligence project analyzing **Blinkit's** (quick-commerce) operations across sales, delivery, customers, inventory, and marketing — built to surface actionable insights for leadership decision-making.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=flat)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-blue?style=flat)

---

## 📌 Project Overview

Blinkit operates in the hyper-competitive quick-commerce space, where **delivery speed, product availability, and customer satisfaction** directly drive revenue. This project consolidates data from **8 interconnected operational sources** into a single Power BI data model to answer core business questions:

- Where is revenue coming from, and which products/categories drive it?
- Are we meeting delivery SLAs, and where are the bottlenecks?
- Who are our most valuable customers, and how do segments differ?
- Is inventory being managed efficiently, or is stock damage eating into margins?
- Which marketing campaigns/channels are actually generating ROI?

The result is an interactive dashboard that turns raw transactional logs into decision-ready KPIs.

---

## 🗃️ Dataset

The model is built on **~100K+ rows** across 8 related tables (star-schema style), covering **March 2023 – November 2024**:

| Table | Description | Rows |
|---|---|---|
| `blinkit_orders.csv` | Order-level transactions — date, total, payment method, delivery status | 5,000 |
| `blinkit_order_items.csv` | Line-item detail per order — product, quantity, price, revenue | 5,000 |
| `blinkit_products.csv` | Product catalog — category, brand, price, MRP, margin %, shelf life | 269 |
| `blinkit_customers.csv` | Customer master — segment, area, registration date, order history | 5,000 |
| `blinkit_delivery_performance.csv` | Promised vs. actual delivery time, distance, delay reasons | 5,000 |
| `blinkit_inventory.csv` | Daily stock received vs. damaged stock by category | 75,000+ |
| `blinkit_marketing_performance.csv` | Campaign-level impressions, clicks, conversions, spend, ROAS | 5,400 |
| `blinkit_customer_feedback.csv` | Order ratings, sentiment, and feedback category | 5,000 |

> Data is synthetically generated to simulate realistic quick-commerce operations for portfolio/learning purposes.

---

## 🎯 Key Business Metrics Modeled

- **Revenue & Orders:** ₹1.1Cr+ total revenue across 5,000 orders, ~2,500 unique customers
- **Delivery Performance:** ~69% orders delivered On Time, ~21% Slightly Delayed, ~10% Significantly Delayed
- **Customer Segmentation:** Premium / Regular / New / Inactive segments with distinct ordering behavior
- **Product Mix:** 11 categories (Fruits & Vegetables, Dairy & Breakfast, Snacks, Personal Care, Pharmacy, etc.)
- **Marketing ROI:** Campaign performance across App, Email, SMS, and Social Media channels
- **Customer Sentiment:** Feedback split across Positive / Neutral / Negative with category-level drivers (delivery, product quality, app experience)
- **Inventory Health:** Stock received vs. damaged stock % by category, to flag high-wastage items

---

## 📊 Dashboard Highlights

The Power BI report (`Blinkit_Project.pbix`) includes multiple pages / views covering:

1. **Sales Overview** — Revenue trends, top categories & products, payment method mix
2. **Delivery Performance** — SLA adherence, delay reasons, delivery partner efficiency
3. **Customer Insights** — Segment-wise value (AOV, order frequency), retention signals
4. **Inventory & Wastage** — Damage % by category, stock trends over time
5. **Marketing Effectiveness** — Channel-wise spend vs. revenue generated, ROAS by campaign
6. **Customer Feedback** — Sentiment distribution and rating trends by feedback category

*(Add screenshots/GIFs of each page here for recruiters to preview without opening Power BI)*

```
📸 [Insert dashboard screenshots here]
```

---

## 🛠️ Tools & Techniques Used

- **Power BI Desktop** — data modeling, relationships, and report design
- **Power Query (M)** — data cleaning, transformation, and shaping across 8 source tables
- **DAX** — calculated measures for KPIs (revenue, AOV, delay %, ROAS, churn signals, etc.)
- **Data Modeling** — star-schema design linking orders, products, customers, delivery, marketing, and feedback
- **Data Visualization** — interactive slicers, drill-throughs, and cross-filtering for exploratory analysis

---

## 💡 Key Insights (example — customize with your actual findings)

- A meaningful share of orders (~30%) fall outside the "On Time" SLA, concentrated in specific delivery partners/areas — a direct lever for improving customer satisfaction.
- Premium and Regular segments contribute disproportionately to revenue relative to their share of the customer base.
- Certain product categories show consistently higher stock damage %, pointing to storage/handling issues worth investigating.
- Marketing spend efficiency (ROAS) varies significantly by channel, suggesting budget reallocation opportunities.

---

## 📁 Repository Structure

```
├── Blinkit_Project.pbix          # Power BI report file
├── data/
│   ├── blinkit_orders.csv
│   ├── blinkit_order_items.csv
│   ├── blinkit_products.csv
│   ├── blinkit_customers.csv
│   ├── blinkit_delivery_performance.csv
│   ├── blinkit_inventory.csv
│   ├── blinkit_marketing_performance.csv
│   └── blinkit_customer_feedback.csv
└── README.md
```

---

## 🚀 How to Use

1. Clone this repository
2. Open `Blinkit_Project.pbix` in **Power BI Desktop**
3. Refresh the data source if prompted (point to the `data/` folder)
4. Explore the report pages using slicers and filters

---

## About This Project

Built as a portfolio project to demonstrate end-to-end data analysis skills: data modeling, DAX, and business storytelling through dashboards — applied to a realistic quick-commerce use case.

**Skills demonstrated:** Data Cleaning · Data Modeling · DAX · Power BI · Business Analysis · KPI Design · Storytelling with Data