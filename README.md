# Istanbul Sales Analysis Dashboard

An interactive Power BI dashboard analyzing retail sales and customer behavior across shopping malls in Istanbul. This was my first Power BI project.

## Overview
The dashboard has two pages: a high-level **Metrics Overview** and a deeper **Mall & Customer Analysis**. It shows which malls, product categories, customer age groups and payment methods drive the most revenue, and how sales change over time.

## Dataset
- **Source:** Kaggle, Istanbul sales dataset (`istanbul_sales_data.csv`)
- **Fields used:** shopping mall, product category, payment method, quantity, price, customer gender, customer age group, order date

## Data Model
Star-schema style model with three tables:
- **Sales** (fact table)
- **Customer** (gender, age group)
- **Date** (year and month hierarchy)

## Dashboard Pages

### 1. Metrics Overview
- **KPI cards:** Total Revenue, Total Orders, Average Order Value, Total Quantity Sold, Average Price
- Monthly and yearly revenue trend by payment method
- Revenue by shopping mall
- Revenue by customer age group
- Quantity sold and revenue by product category
- Orders by payment method
- Quantity sold by customer gender

### 2. Mall & Customer Analysis
- Revenue by shopping mall
- Revenue share by gender
- Mall performance table: orders, revenue, average order value and payment method

**Interactivity:** year slicer, page navigation buttons and cross-filtering between visuals.

## Tools Used
- Power BI Desktop (data modeling, DAX measures, visualization)

## Repository Contents
| File | Description |
|------|-------------|
| `Replicate_dash.pbix` | Power BI dashboard file |

## How to Use
1. Download `Replicate_dash.pbix`.
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Use the year slicer and navigation buttons to explore the dashboard.



## Author
**Alizeh Qamar**
