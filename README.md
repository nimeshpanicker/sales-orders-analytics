# 📊 Sales Orders Analytics Dashboard

![Sales Analytics](https://img.shields.io/badge/Sales-Analytics-blue)
![Dashboard](https://img.shields.io/badge/Interactive-Dashboard-cyan)
![Data Visualization](https://img.shields.io/badge/Data-Visualization-orange)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-purple)
![Status](https://img.shields.io/badge/Project-Completed-success)

> An interactive Sales Orders Analytics project analysing revenue, profit,
> orders, customers, products, regions, categories, order status, and
> operational performance across 44 months of sales data.

---

# 📌 Project Overview

This project analyses sales-order data covering the period from
**20 January 2023 to 17 August 2026**.

The dataset contains **500 unique sales orders** with **16 columns** covering
sales transactions, customers, products, geography, financial measures,
customer segments, and order status.

The project transforms transactional sales data into an interactive
analytics dashboard designed to support business performance monitoring and
data-driven decision making.

The analysis focuses on:

- Revenue
- Profit
- Profit Margin
- Orders
- Units Sold
- Average Order Value
- Customer Performance
- Product Performance
- Category Performance
- Regional Performance
- State-Level Performance
- Customer Segments
- Order Status
- Monthly and Quarterly Trends

---

# 🎯 Project Objectives

The main objectives of this project are:

- Analyse overall sales and profitability.
- Monitor revenue and profit performance.
- Calculate key sales and operational KPIs.
- Analyse monthly, quarterly, and yearly trends.
- Identify high-performing customers.
- Analyse product and category performance.
- Compare revenue across regions and states.
- Analyse customer-segment contribution.
- Monitor order-status and fulfilment performance.
- Identify revenue concentration across customers.
- Analyse average order value and order size.
- Provide interactive filtering across business dimensions.
- Create a row-level Records view for detailed analysis.
- Translate analytical findings into business insights and recommendations.

---

# 📊 Dataset

The project uses a sales-order dataset containing **500 unique orders**.

| Dataset Attribute | Details |
|---|---|
| Row Count | **500 orders** |
| Unique Orders | **500** |
| Date Range | **20 Jan 2023 – 17 Aug 2026** |
| Coverage | **44 months** |
| Columns | **16** |
| Null Values | **None** |
| Row Grain | **One row per sales order** |
| Regions | **4** |
| States | **10** |
| Customer Segments | **3** |
| Categories | **4** |
| Products | **12** |
| Customers | **18** |
| Order Statuses | **4** |

The dashboard supports daily, weekly, monthly, quarterly, and yearly
analysis.

---

# 🗂️ Dataset Structure

## Identifier

- Order ID

## Date & Calendar Fields

- Order Date
- Year
- Quarter
- Month

## Grouping Dimensions

- Region
- State
- Customer
- Customer Segment
- Category
- Product

## Numeric Measures

- Quantity
- Unit Price
- Revenue
- Cost
- Profit

## Status

- Completed
- Pending
- Processing
- Cancelled

---

# 🧹 Data Preparation & Validation

The source dataset was profiled before dashboard development.

The following validation checks were performed:

- Confirmed **500 unique order IDs**.
- Confirmed one row represents one sales order.
- Checked all 16 columns.
- Verified there are no null values.
- Validated revenue calculations.
- Validated profit calculations.
- Reconciled dashboard totals against the source dataset.
- Verified available dimensions and filter values.
- Tested dashboard filtering behaviour.
- Tested dashboard rendering.
- Tested production build and live-page functionality.

### Financial Validation

```text
Revenue = Quantity × Unit Price

Profit = Revenue − Cost
