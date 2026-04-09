# BI Star Schema Data Warehouse Project

## Tools Used
Python, SQLite, SQL, Power BI

## What I Built
- Designed a star schema with 1 fact table and 4 dimension tables
- Loaded and transformed Superstore sales data using Python/Pandas
- Wrote OLAP-style SQL queries for slicing data by time, region, product
- Built an interactive Power BI dashboard with sales, regional, and product analysis

## Schema Design
fact_sales → dim_date, dim_customer, dim_product, dim_region

## Files
- star_schema_build.ipynb — schema creation
- olap_queries.ipynb — analytical queries
- export_csv.py — CSV export for Power BI
- dashboard.pbix — Power BI report