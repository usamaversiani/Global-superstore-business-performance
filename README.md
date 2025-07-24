# Global-superstore-business-performance

 **Interactive business analytics dashboard for global retail chain data.**

## Dataset
- Source: [Kaggle - Global Superstore](https://www.kaggle.com/)
- Format: CSV (~50,000 rows)
- Fields: Sales, Profit, Customer, Product, Region, Shipping Cost, Discount

## Tools & Technologies
- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Star Schema Modeling
- KPI & Visual Storytelling

## Data Model
- Fact Table: `Orders`
- Dimension Tables: `Customers`, `Product`, `Geography`, `DateTable`
- Relationships: Star schema via keys (`Customer ID`, `Product ID`, `Date`)

## Key DAX Measures
- `Sales YTD`, `Profit YTD`, `YoY Growth`, `Shipping Cost`, `Profit Margin`, etc.

## Dashboard Pages
1. **Executive Summary** – Sales, profit, YoY growth, top countries & categories
2. **Product Performance** – Profitability by product, discount impact
3. **Customer & Region** – Segment trends, market maps, top customers

## Business Insights
- Pinpointed high-discount low-profit items
- Identified most profitable customer segments
- Visualized YoY growth and shipping efficiency

