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

## Power BI Report:
### Dashboard 1: Key Insight
![Key_Insight_Dashboard](https://github.com/YanhuaB/AtliQ-hardware/blob/main/PowerBI_Files/dashboards/key_insight.jpg)

The revenue trend was analyzed to provide a comprehensive overview of the company's performance over the years. Utilizing card, slicer functions, and 
bar charts, the data in the dashboard was made easily accessible. This setup allowed for straightforward examination of revenues and sales amounts by
year or month, with detailed distribution across different markets and product lines.
### Dashboard 2: Profit
![Profit_Dashboard](https://github.com/YanhuaB/AtliQ-hardware/blob/main/PowerBI_Files/dashboards/Profit.jpg)
For the second dashboard, building upon the insights from the first, the analysis focused on customer revenue contributions. It provided an in-depth 
examination of the top customers in different cities and their profit margin contributions.
### Dashboard 3: Performance Insight
![Performance_Insight_Dashboard](https://github.com/YanhuaB/AtliQ-hardware/blob/main/PowerBI_Files/dashboards/Performance_Insight.jpg)
For the final dashboard, the focus was on illustrating branch performance across different markets. By analyzing revenue and profit trends in various cities, the dashboard provided valuable insights for branch management.
## Conclusion:
In conclusion, the three-perspective dashboard I developed has significantly improved data accessibility and supported robust data-driven decision-making processes. By providing detailed insights into revenue trends, customer behavior, and market dynamics, the dashboard has empowered stakeholders across the organization. 

Through rigorous data cleaning processes including deduplication, currency normalization, and removal of low-quality data, we ensured the accuracy and reliability of our analyses. Integration of a MySQL database with Power BI facilitated efficient data modeling and ETL operations, resulting in substantial time savings.

The dashboard not only enhanced accessibility for non-technical stakeholders but also enabled clear and actionable insights through intuitive visualizations. By mapping key relationships among our datasets, we have enabled comprehensive analysis of sales performance, customer contributions by city, and branch effectiveness across diverse markets. This holistic approach ensures that our insights are not only accessible but also impactful in driving strategic decisions and optimizing business outcomes.
