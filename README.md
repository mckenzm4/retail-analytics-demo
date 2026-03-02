# Retail Sales Analytics Demo

A portfolio data project demonstrating end-to-end analytics on a synthetic retail sales dataset — from raw CSV to interactive Power BI dashboard.

## Dataset

**`retail_sales.csv`** — 500 rows of simulated retail transaction data across 4 regions and 5 product categories (2024).

| Column | Type | Description |
|---|---|---|
| `date` | DATE | Transaction date |
| `region` | STRING | Sales region (Midwest, Northeast, Southeast, West) |
| `category` | STRING | Product category (Produce, Dairy, Bakery, Frozen, Beverages) |
| `product` | STRING | Product name |
| `units_sold` | INT | Units sold per transaction |
| `unit_price` | FLOAT | Sale price per unit |
| `revenue` | FLOAT | Gross revenue (units × price) |
| `cost` | FLOAT | Cost of goods sold |
| `profit` | FLOAT | Gross profit (revenue − cost) |

## Key Questions Explored

- Which regions drive the most revenue and profit?
- How do margins vary by product category?
- What does monthly revenue trend look like over 2024?
- Which products are the top performers by profit?

## Tools Used

- **Python** — data generation and validation
- **Power BI** — interactive dashboard (embed below)
- **GitHub** — version control and project hosting

## Power BI Dashboard

> 📊 *Dashboard link coming soon — open `retail_sales.csv` in Power BI Desktop to explore.*

## How to Use

```bash
# Clone the repo
git clone https://github.com/mckenzm4/retail-analytics-demo.git

# Open retail_sales.csv in Power BI Desktop
# or load into Python:
import pandas as pd
df = pd.read_csv('retail_sales.csv')
df.head()
```
