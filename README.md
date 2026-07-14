# Madhav Ecommerce Sale Dashboard 🛒

A Power BI dashboard analyzing e-commerce orders — sales, profit, quantity, and customer/geography breakdowns — for a quick executive view of performance.

## Overview
Report titled **"Madhav Ecommerce Sale Dashboard"**, showing revenue/profit trends, top states/customers, category performance, and payment mix.

## File
- `project_1.pbix` — open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/).

## Dashboard Contents
**KPIs**
- Total Amount (Sales)  
- Total Quantity  
- Total Profit  
- Average Order Value (AOV)  

**Visuals**
| Visual | Type | Breakdown |
|---|---|---|
| Profit by Month | Column | Order Date (Month) |
| Profit by Sub-Category | Funnel | Sub-Category |
| Quantity by Category | Donut | Category |
| Quantity by Payment Mode | Donut | Payment Mode |
| Sales by State | Bar | State |
| Sales by Customer | Column | Customer Name |
| Quarter Filter | Slicer | Order Date (Quarter) |
| State Filter | Slicer | State |

## Data Model
Two tables:  
- **Orders** — order-level info (`Order Date`, `State`, `Customer Name`)  
- **Details (1)** — line-item info (`Category`, `Sub-Category`, `PaymentMode`, `Quantity`, `Amount`, `Profit`)  

Measure: **AOV** (Average Order Value).

## Key Questions
- Profit trend month over month  
- Top sub-categories/categories by profit & volume  
- States/customers driving sales  
- Preferred payment methods  
- Average order value  

## Usage
1. Install Power BI Desktop.  
2. Open `project_1.pbix`.  
3. Use Quarter/State slicers to filter.  
4. Hover charts for tooltips.  
5. (Optional) Publish to Power BI Service.

## Tech Stack
- Power BI Desktop  
- Power Query  
- DAX  

