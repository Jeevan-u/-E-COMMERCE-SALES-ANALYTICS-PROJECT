# E-Commerce Sales Analytics Project

An end-to-end data analytics project on Brazilian e-commerce public dataset by Olist. This project performs comprehensive sales analysis, customer behavior insights, and visualization using Python.

## Project Overview

This mini project analyzes ~100k orders from 2016–2018 to uncover actionable business insights. The analysis pipeline includes data loading, cleaning, merging multiple datasets, exploratory analysis, and visualisation — all within a single Jupyter Notebook.

## Key Analyses

- **Total Revenue** – Overall revenue calculation from order items
- **Monthly Sales Trends** – Revenue patterns across months to identify peak periods
- **Top Selling Products** – Best performing product categories
- **Payment Method Analysis** – Distribution of payment types used by customers
- **Geographic Revenue** – Top states and cities contributing highest revenue
- **Order Status Analysis** – Breakdown of order delivery performance
- **Customer Review Analysis** – Review score distributions and satisfaction patterns
- **Seasonal Patterns** – Sales fluctuations across seasons for inventory planning
- **Correlation Heatmap** – Relationship between numerical features

## Dataset

The dataset is the Brazilian E-Commerce Public Dataset by Olist, consisting of 9 CSV files:

| Dataset | Description |
|---|---|
| `olist_customers_dataset` | Customer information and location |
| `olist_orders_dataset` | Order details and timestamps |
| `olist_order_items_dataset` | Item-level order data |
| `olist_order_payments_dataset` | Payment transaction details |
| `olist_order_reviews_dataset` | Customer review scores |
| `olist_products_dataset` | Product category information |
| `olist_sellers_dataset` | Seller information and location |
| `olist_geolocation_dataset` | ZIP code geolocation data |
| `product_category_name_translation` | Portuguese-to-English category translations |

## Tech Stack

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Google Colab**

## Business Insights

1. Top product categories generate the highest revenue
2. Monthly trends identify peak shopping periods
3. Most customers prefer digital payment methods
4. Certain states contribute the highest revenue
5. Customer reviews indicate overall satisfaction levels
6. Seasonal patterns help in inventory planning
7. Revenue analysis supports better business decision-making

## How to Run

Open `Mini_project.ipynb` in Jupyter Notebook or Google Colab and run all cells. The final report is exported as `Final_Ecommerce_Analytics_Report.csv`.

---

**Directed by** – Satyam Sir

**Prepared by** – Jeevan KL & Towhid Alam
