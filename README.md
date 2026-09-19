# E-Commerce Intelligence ” Looker & LookML Portfolio Project

## Overview

**E-Commerce Intelligence** is an end-to-end Business Intelligence project built in **Looker** using **LookML** and a BigQuery e-commerce dataset.

The project is organized around three business perspectives:

- **Executive Overview**  overall commercial performance and high-level trends
- **Sales Intelligence**  revenue, order status, product department, and category performance
- **Product Intelligence**  product pricing, profitability, margins, and category-level pricing behavior
- **Customer Intelligence**  customer geography, age profile, acquisition channels, and purchase behavior

The objective was to turn raw e-commerce data into a connected analytics experience that supports both executive monitoring and deeper business analysis.

## Key Technologies

- **Looker**
- **LookML**
- **SQL**
- **Google BigQuery**
- Data modeling with Explores, joins, dimensions, measures, dimension groups, and derived tables
- Interactive dashboards and business-focused visualizations

## Data & Modeling

The project uses the Google Cloud e-commerce training dataset available through the BigQuery environment.

The LookML model connects core business entities including:

- Orders / Order Items
- Users
- Products
- Inventory Items
- Distribution Centers
- Events / Sessions

A session-level derived table was also used to support customer behavior and funnel analysis.

### Modeling highlights

- Reusable LookML dimensions and measures
- `many_to_one` relationships between core entities
- Date/time analysis through dimension groups
- Return-rate calculation
- Average Order Value (AOV)
- Product margin and pricing metrics
- Session-level behavioral analysis
- Dashboard-ready business metrics

## Dashboard Structure

### 1. Executive Overview

Provides a high-level view of business performance.

Key metrics shown in the dashboard include:

- **Total Orders:** 332,947
- **Total Revenue:** $15,578,336.23
- **Average Order Value:** $46.79
- **Total Customers:** 85,882

Supporting views include:

- Monthly Revenue Trend
- Top 10 Products
- Revenue by Traffic Source
- Customer Conversion Funnel
- Revenue by Category

### 2. Sales Intelligence

Focuses on where revenue is generated and how orders are distributed.

Views include:

- Revenue by Order Status
- Order Volume by Status
- Revenue by Product Department
- Revenue by Product Category

### 3. Product Intelligence

Focuses on product economics and pricing behavior.

Views include:

- Total Product Margin
- Category Pricing Analysis
- Average Margin by Category
- Product Profitability Detail
- Retail Price vs Average Sale Price

### 4. Customer Intelligence

Focuses on customer composition, acquisition, geography, and purchasing behavior.

Views include:

- Customer Distribution by Country
- Customer Age Profile
- Customer Acquisition by Traffic Source
- Customer Purchase Behavior

## Business Questions Answered

The dashboards were designed to answer questions such as:

1. How much revenue and order volume is the business generating?
2. How is revenue changing over time?
3. Which products and categories contribute the most revenue?
4. Which product categories generate stronger margins?
5. Which traffic sources bring the largest customer volumes?
6. Which traffic sources contribute the most revenue?
7. What does the customer age and geographic profile look like?
8. How do customer acquisition channels differ by market?
9. Which products show strong pricing and margin characteristics?
10. Where are the main opportunities for commercial optimization?

## Key Takeaways

The dashboard evidence shows several clear patterns:

- Revenue is highly concentrated in a small number of product categories, with **Jeans** leading the category view.
- **Search** is the dominant acquisition channel by both customer volume and revenue.
- The customer base is concentrated in the **under-18** and **35“54** age groups, with additional volume in older segments.
- The product margin analysis shows substantial variation across categories, indicating different profitability profiles.
- Retail price and average sale price display a strong positive relationship across products.
- The order-status analysis shows that **Completed** orders dominate revenue and order volume.
- The customer purchase table shows strong revenue concentration in the **USA / Search** combination.

## Portfolio Value

This project demonstrates more than dashboard creation. It shows the ability to:

- Translate business questions into analytical metrics
- Build a reusable semantic layer with LookML
- Combine transactional and behavioral data
- Create derived/session-level analytical structures
- Build executive and operational dashboards
- Identify commercially relevant patterns from data
- Present BI results in a portfolio-ready format

## Suggested Repository Structure

```text
e-commerce-intelligence-looker/
 README.md
 BUSINESS_INSIGHTS.md

 lookml/
 model/
 views/
 dashboards/

 screenshots/
 executive-overview.png
 sales-intelligence.png
 product-intelligence.png
 customer-intelligence.png

 documentation/
project_notes.md```

## Author

**Business Intelligence Portfolio Project**

Focus areas: **Looker | LookML | SQL | BigQuery | Data Modeling | Dashboard Design | Business Analysis**
