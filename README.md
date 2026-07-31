# Olist Customer Dissatisfaction Analysis

Business Intelligence project analyzing the key drivers of customer dissatisfaction in the Olist e-commerce marketplace using Power BI.

## Project Summary

**Objective:** Identify the main drivers of customer dissatisfaction in the Olist marketplace.

**Dataset:** Olist Brazilian E-commerce Public Dataset *(Kaggle)*

**Tools:** Power BI · Power Query · DAX

**Focus Areas:** Customer Reviews · Delivery Performance · Product Categories · Order Complexity

---

## Project Overview

This project investigates the factors contributing to customer dissatisfaction in the Olist marketplace by analyzing customer reviews in relation to delivery performance, product categories, and order complexity. The objective is to identify the main drivers of negative customer experiences and uncover actionable business insights.

## Business Questions

- What are the main drivers of customer dissatisfaction?
- How does delivery performance affect customer reviews?
- Which product categories receive the most negative reviews?
- Does order complexity influence customer ratings?

## Dashboard Overview

![Dashboard Overview](01-Dashboard.png)

This dashboard provides an overview of customer dissatisfaction in the Olist marketplace, highlighting key metrics, review distribution, delivery performance, and the main factors associated with negative customer feedback.

---

## Key Finding 1: Delivery Performance

![Negative Reviews by Delivery Delay](02-Negative%20Ratings%20by%20Delivery%20Delays.png)

Customer dissatisfaction increases significantly as delivery delays become longer. While only 12% of on-time deliveries receive negative reviews, this percentage rises steadily with each additional day of delay, reaching 77% for deliveries delayed by six or more days.

---

## Key Finding 2: Category-Level Analysis

![High-Volume Product Categories](03-Reviews%20Through%20Categories.png)

Among high-volume product categories, **bed_bath_table** stands out with the highest negative review rate, while **health_beauty** exhibits a much lower percentage despite a similarly high order volume. This comparison helps identify categories where improvement efforts may have the greatest business impact.

---

## Key Finding 3: Category-Level Analysis (Excluding Late Deliveries)

![Product Categories (Early / On Time Deliveries)](04-Reviews%20Through%20Categories-Filtered.png)

To isolate the effect of delivery performance, late deliveries were excluded from the analysis. Even among early and on-time deliveries, some product categories continue to show relatively high negative review rates, suggesting that product-related factors may also contribute to customer dissatisfaction.

---

## Key Finding 4: Order Complexity

![Negative Reviews in Multi-Item Orders](05-Ratings%20by%20Number%20of%20Items.png)

Orders containing multiple products receive considerably more negative reviews than single-item orders, even when deliveries are made on time. This suggests that larger orders may present additional challenges affecting the customer experience.

---

## Key Insights

- Customer dissatisfaction increases sharply as delivery delays become longer.
- Certain high-volume product categories consistently exhibit higher negative review rates.
- Multi-item orders are associated with significantly higher negative review rates, even for on-time deliveries.

---

## Business Value

The analysis highlights actionable opportunities to improve customer experience by reducing delivery delays, prioritizing product categories with consistently high negative review rates, and investigating operational challenges associated with multi-item orders.
