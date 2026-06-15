## 📌 Project Description

This project replicates a real-world corporate data analytics workflow for a computer hardware manufacturer. The company was facing declining sales in a highly dynamic market, and the Sales Director struggled to get accurate insights from messy Excel files and subjective verbal updates from regional managers.

To solve this, I built an end-to-end Business Intelligence solution that replaces manual reporting with an automated, interactive dashboard, shifting the company from gut-feeling decisions to **data-driven strategies**.

### 🛠️ Technical Workflow & Implementation

1. **Data Discovery & Database Setup**: 
   * Linked a MySQL database containing sales transactions, customer records, products, and market data.
   * Executed SQL queries to explore schema structures, check record counts, and perform initial data validation.

2. **Data Cleaning & ETL (Power Query)**:
   * Handled data anomalies, filtered out invalid transaction values (e.g., zero or negative sales values).
   * Normailzed currency inconsistencies (converting USD transactions to INR for standardized reporting).
   * Cleaned up blank regional entries to ensure clean data formatting.

3. **Data Modeling & DAX**:
   * Designed a robust **Star Schema** by establishing relationships between the fact table (`fact_sales`) and dimension tables (`dim_customers`, `dim_products`, `dim_markets`, `dim_date`).
   * Created key business metrics using **DAX (Data Analysis Expressions)**, including Total Revenue, Sales Quantity, and dynamic date filtering.

4. **Dashboard Design & Insights**:
   * Engineered a highly intuitive dashboard layout tracking top clients, profit trends, revenue contribution by zone, and lowest-performing regions.
   * Implemented interactive filters allowing stakeholders to slice data by year, month, and market instantly.
