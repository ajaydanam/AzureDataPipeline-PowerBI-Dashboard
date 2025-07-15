# Azure Data Pipeline-Power BI-Dashboard

End-to-end ETL pipeline design using Azure Data Factory, Azure Blob Storage, Azure SQL Database, and Power BI for data visualization.

This is a full-scale Power BI project built from raw `.csv` files of the [Olist E-Commerce dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). The goal is to simulate a real-world data pipeline, perform transformations, build KPIs, and generate dashboards using best BI practices.


This is a full-scale Power BI project built from raw `.csv` files of the [Olist E-Commerce dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). The goal is to simulate a real-world data pipeline, perform transformations, build KPIs and generate dashboards using best BI practices.

------

##  🔗  Project Overview

- Data Source: 9 CSV files uploaded from Azure Blob Storage
- ETL Pipeline: Data cleaned and modeled in Power BI Power Query
- Data Modeling: Star schema built with calendar table, key relationships and DAX measures
- Visualization: Multiple report pages covering KPIs, trends, customer behavior and reviews

------

## 📁 Folder Structure

AzureDataPipeline-PowerBI-Dashboard/
├── Data/ ← Raw CSV files
├── Images/ ← Power BI dashboard screenshots
├── Power BI/
│ ├── Measures/ ← All the DAX measures
│ └── Report/ ← Final .pbix file
├── SQL/ ← SQL scripts to create schema tables in Azure SQL Database
└── README.md ← You are here

------

##  🧠  Key DAX Measures

- Orders: Total, YTD, MTD, Cancelled, Delivered, On-Time %
- Revenue: Total, per Order, YTD/MTD, Avg Installments
- Customers: Unique, Returning, Revenue per Customer
- Products: Avg Dimensions, Missing Fields, Category Analysis
- Reviews: Avg Score, 5-Star %, Response Time
- Sellers: Revenue per Seller, Orders per Seller

> ⚙️  View all DAX logic under `/Power BI/Measures

------

##  📊  Visual Insights

Uploaded high-resolution screenshots of report pages for visual reference:

• executive_dashboard.png – Showcases key e-commerce metrics including Total Orders, Revenue, Category Performance, and Geo insights.

• order_fulfillment_dashboard.png – Visualizes order status breakdown, average delivery times, and fulfillment efficiency across periods.

These visuals will be embedded in the main README to help viewers quickly understand the scope and design of the Power BI dashboards built as part of the Azure Data Pipeline project.


------

##   🚀 Built With

- Power BI (DAX, Power Query, Relationships)
- Azure Blob Storage (CSV Data Source)
- SQL (Azure SQL Database)
- GitHub (Documentation & Versioning)

------

## 👨‍💻 Author

**Ajay Danam**  
[LinkedIn](https://www.linkedin.com/in/ajaydanam) | Data Analyst | BI Developer | Healthcare, Commercial, operational & Financial Analytics.

