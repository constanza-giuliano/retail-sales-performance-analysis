# Retail Sales Performance Analysis
Sales performance and profitability analysis developed using Power BI to support commercial decision-making in a retail environment.

## Context
A mid-sized technology retail company required a comprehensive analysis of its sales performance to better understand revenue generation, cost structure, and profitability drivers across its operations.
The sales department needed a centralized analytical solution to evaluate monthly performance, monitor gross profitability, and identify opportunities for commercial optimization across products, store locations, and regions.
The objective was to transform transactional sales data into actionable insights that could support tactical decision-making related to pricing strategies, product performance, inventory planning, and sales management.
To address this need, an interactive Business Intelligence dashboard was developed in Power BI, enabling stakeholders to analyze key performance indicators through multiple business dimensions such as time, product hierarchy, suppliers, and geographic distribution.

## Objectives
- Valuate overall sales performance and revenue evolution over time.
- Analyze gross profitability to understand margin behavior across products and locations.
- Identify top-performing and underperforming products based on sales volume and profitability.
- Compare performance across regions and store locations to detect operational differences.
- Understand supplier contribution to total revenue and profitability.
- Enable dynamic filtering and exploratory analysis to support data-driven decision-making by business stakeholders.

## Technical Stack
**Business Intelligence & Visualization**

- Power BI: Interactive dashboard development and data visualization

**Data Preparation**

- Power Query: Data cleaning, transformation, and normalization

**Data Modeling**

- Star schema design
- Relationship management between fact and dimension tables

**Data Analysis**

- DAX (Data Analysis Expressions) – Measures and calculated metrics for sales and profitability analysis

**Data Source**
- Structured retail sales dataset (transactional data model)

## Notes on Data
The analysis uses a structured retail sales dataset organized under a dimensional data model to support multidimensional performance analysis.

Data Model: Sales fact table containing transaction-level metrics such as revenue, quantity, and cost.
Supporting dimensions including products, suppliers, locations, and calendar data.

Data Preparation: Data was cleaned and transformed using Power Query to ensure consistency, create analytical fields, and validate relationships across tables.

Scope: Profitability analysis focuses on gross profit, as operational expenses were not included in the dataset.

## Screenshots

### Sales & Profitability — Overview
This page provides a comprehensive overview of overall sales performance and gross profitability. It highlights key financial indicators such as total revenue, cost of goods sold, gross profit margin, and average daily performance. The dashboard enables stakeholders to monitor business health, compare profitability across branches and regions, and identify revenue trends over time to support commercial decision-making.
![Sales & Profitability](images/1. Sales_Profability.png)
