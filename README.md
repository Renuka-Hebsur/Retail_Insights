# 🛍️ Retail Insights: Sales Analytics Project

This repository is a complete retail sales analytics project using SQL and Tableau. It includes raw sales data, structured SQL queries for analysis, and a Tableau dashboard for visualization.

## 📁 Project Files

| File Name | Description |
|-----------|-------------|
| `data.csv` | Raw dataset containing 5,000 retail sales records |
| `retail_insights_data.sql` | MySQL dump with table schema and pre-written queries |
| `Retail_Insights.twbx` | Tableau packaged workbook for data visualization |

---

## 🧾 Dataset Overview

This dataset includes sales order data with fields covering:

- **Customer Info**: Name, Address, City, State, Customer Type
- **Order Info**: Order No, Order Date, Ship Date, Order Priority
- **Product Info**: Name, Category, Container
- **Pricing**: Cost Price, Retail Price, Profit Margin, Discounts
- **Logistics**: Ship Mode, Shipping Cost
- **Financials**: Order Quantity, Subtotal, Discount $, Order Total, Final Total

> **Note:** Many monetary fields contain currency symbols and need preprocessing for numerical analysis.

---

## 🧠 Analysis Goals

Using SQL and Tableau, this project aims to answer the following business questions:

- 🧾 What is the **total revenue**, **average order value**, and **profit margin**?
- 📦 Which are the **top-performing products** and **categories**?

## 🛠️ Tools & Technologies

- **SQL (MySQL 8.0)** – Data querying and transformation
- **Tableau** – Interactive dashboard development

📌 Summary & Key Insights
💰 Revenue & Profitability

The business generated substantial revenue across multiple product categories, with certain high-margin items contributing disproportionately to overall profit.

Discounts, while boosting order volume in some segments, often reduced profitability and should be monitored closely.

📦 Product Performance

A small subset of products (likely in the "Office Supplies" category) accounted for the majority of revenue.

Some low-cost, high-volume products had thin profit margins but were essential for customer retention.

👥 Customer Segmentation

Corporate clients generated higher order values on average, while small businesses showed more frequent orders with smaller totals.

Key account managers played a significant role in high-value orders.

🚚 Shipping & Logistics

Express Air shipping modes were associated with higher-priority orders but increased overall costs.

Shipping cost optimization is a potential area for improving margins.

⚠️ Order Priority

“Critical” priority orders had high revenue impact but also tended to include higher shipping and fulfillment costs.

Not all high-priority orders were high-margin—some were driven by steep discounts

✅ Conclusion & Next Steps
This project provided actionable insights into retail operations by analyzing sales, customer behavior, and logistics using SQL and Tableau. The combination of data-driven queries and visual dashboards helps uncover trends that can inform inventory planning, marketing strategies, and operational efficiency.

Next Steps:

Implement regular monitoring of product-level profitability.

Optimize discount strategies to avoid margin erosion.

Expand dashboards to include predictive analytics or regional forecasting.

Integrate Python-based analysis for deeper statistical modeling.
