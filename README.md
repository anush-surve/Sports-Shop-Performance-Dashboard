# Sports Shop Sales Performance Dashboard

An interactive Excel dashboard that tracks sales, profit and customer trends for a sports retail shop, built from 100 invoices (20 Jul – 13 Oct 2026).

## What's inside

| Sheet | Description |
|---|---|
| **Dashboard** | KPI cards (Total Revenue, Total Profit, Quantity Sold, Average Revenue), five charts and interactive slicers |
| **Pivot Table** | PivotTables that feed the dashboard charts and KPIs |
| **Sports Sales** | Raw transaction data with formula-driven Revenue, Cost, Profit and Profit % columns |

## Dashboard views

- Revenue by Month
- Revenue by City (Mumbai, Pune, Nashik, Satara)
- Revenue by Product Category (Footwear, Cricket, Tennis, Badminton, etc.)
- Top 5 Products
- Revenue by Payment Mode (Cash, Card, UPI)

Slicers/timeline filters: **City**, **Category**, **Discount %**, **Month**.

## Data columns

`Invoice No`, `Date`, `Customer Name`, `City`, `Product`, `Category`, `Brand`, `Qty`, `MRP`, `Cost Price`, `Discount %`, `Revenue`, `Total Cost`, `Profit`, `Profit %`, `Payment Mode`

Key formulas: `Revenue = Qty × MRP × (1 − Discount %)`, `Profit = Revenue − Total Cost`.
