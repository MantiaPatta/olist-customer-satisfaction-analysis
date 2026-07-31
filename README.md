# Olist Customer Dissatisfaction Analysis

Business Intelligence project analyzing the key drivers of customer dissatisfaction in the Olist e-commerce marketplace using Power BI.

## Project Overview

This project investigates the factors that influence customer satisfaction in the Olist marketplace by analyzing customer reviews in relation to delivery performance and other order-related factors. The objective is to identify patterns that can help improve the overall customer experience.

## Business Questions

- What are the main drivers of customer satisfaction and dissatisfaction?
- How does delivery performance affect customer reviews?
- Which product categories receive the most negative reviews?
- How do order characteristics influence customer ratings?

## Tools Used

- Power BI
- Power Query
- DAX

## Dashboard Overview

![Dashboard Overview](01-Dashboard.png)

This dashboard provides an overview of customer dissatisfaction in the Olist marketplace, highlighting key metrics, review distribution, delivery performance, and the main factors associated with negative customer feedback.

---

## Key Finding 1: Delivery Performance

![Negative Reviews by Delivery Delay](02-Negative%20Ratings%20by%20Delivery%20Delays.png)

Customer dissatisfaction increases significantly as delivery delays become longer. While only 12% of on-time deliveries receive negative reviews, this percentage rises steadily with each additional day of delay, reaching 77% for deliveries delayed by six or more days.

---

## Key Finding 2: High-Risk Product Categories

![High-Volume Product Categories](03-Reviews Through Categories.png)

Among high-volume product categories, **bed_bath_table** stands out with the highest negative review rate, while **health_beauty** achieves a much lower percentage despite a similarly high order volume. This helps identify categories where improvement efforts may have the greatest impact.

---

## Key Finding 3: Product Categories Beyond Delivery Performance

![Product Categories (Early / On Time Deliveries)](04-Reviews Through Categories-Filtered.png)

To isolate the effect of delivery performance, late deliveries were excluded from the analysis. Even among early and on-time deliveries, some product categories continue to show relatively high negative review rates, suggesting that product-related factors may also contribute to customer dissatisfaction.

---

## Key Finding 4: Multi-Item Orders

![Negative Reviews in Multi-Item Orders](05-Ratings by Number of Items.png)

Orders containing multiple products receive considerably more negative reviews than single-item orders, even when deliveries are made on time. This suggests that larger orders may present additional challenges affecting the customer experience.

---

## Key Insights

- Customer dissatisfaction increases sharply as delivery delays become longer.
- Certain high-volume product categories consistently receive higher negative review rates.
- Delivery delays are not the only factor affecting customer dissatisfaction.
- Multi-item orders are associated with significantly higher negative review rates, even for on-time deliveries.

---

## Repository Contents

- **README.md** – Project documentation and findings.
- **Power BI Dashboard Screenshots** – Key visualizations from the analysis.
