# Sales Insights of AtliQ hardware- Brick & Mortar business

## Project Description
Built a three-perspective dashboard in a real-life scenario, providing sales insights to support data-driven decision-making 
and empowering non-technical stakeholders with accessible and intelligible information. In this project, improved data accuracy 
by deduplicating raw data, normalizing currency, and cleaning infeasible sales quantities, resulting in the removal of 5% of 
low-quality data. Integrated a MySQL database with Power BI and structured data modeling, identifying and mapping key relationships 
among five tables using primary and foreign keys. Conducted ETL operations in Power Query Editor for dashboard creation, saving 75% 
of the time on data processing.

## Tools Utilized:
Power BI & MySQL

## Dataset
This dataset description provides a comprehensive overview of the sales data of AtliQ hardware, including customer profiles, 
date time information, market details, product information, and transaction records. Here's a summary of the dataset:
- Customers:
  
  **customer_code:** Unique customer identifier
  
  **custmer_name:** Name of the customers
  
  **customer_type:** Business types of customers
  
  
- Date:

  **date:** Date time information in yyyy-mm-dd format
  
  **cy_date:** Nomalized data in the first day of the month
  
  **year:** Year of the date
  
  **month_name:** Month of the date
  
  **date_yy_mmm:** Data in yy-mmm format
  
- Market:
  
  **markets_code:** Unique code of markets identifier 
  
  **markets_name:** Name of the market
  
  **zone:** the location of the market
  
- Product:
  
  **product_code:** Unique product identifier
  
  **product_type:** Type of the product line
  

  
- Transaction:

  **product_code:** Foriegn key from the _Product Table_
  
  **customer_code:** Foriegn key from the _Customer Table_
  
  **market_code:** Foriegn key from  the _Market Table_
  
  **order_date:** Date of the transaction
  
  **sales_qty:** Sales quality of the transaction
  
  **sales_amount:** Sales amount of the transaction
  
  **currency:** Currency type of the transaction
  
  **profit_margin_percentage:** Profit margin percentage
  
  **profit_margin:** Profit margin amount.
  
  **cost_price:** Cost price of the product.

## Dashboard
#### 1
#### 2
#### 3
