# Car_Sales_Performance_Analysis
Project Title:
Car Sales Performance Analysis

Dashboard Preview:
![page1](https://github.com/Pujiwara/Pictures/blob/main/Car%20Sales%20Performance_page-0001.jpg)
![page2](https://github.com/Pujiwara/Pictures/blob/main/Car%20Sales%20Performance_page-0002.jpg)
![page3](https://github.com/Pujiwara/Pictures/blob/main/Car%20Sales%20Performance_page-0003.jpg)

Description:
This project is a comprehensive analysis of the USA Car Sales Dataset 2018–2024. The dataset provides a rich, multidimensional view of individual car sales transactions, including customer details, car specifications, pricing metrics, payment methods, sales performance, and seasonal or regional context.
The main goal of this project is to build a complete end-to-end analytics pipeline, starting from PostgreSQL data warehouse design, ETL transformations, and culminating in an interactive Power BI dashboard for business insight exploration.

Tools Used:
PostgreSQL
Power BI

Key Insights:
1. Total sales remain stable with an upward trend, and profits follow the same pattern — indicating a healthy and stable business.
2. The company maintains a healthy profit margin (16%).
3. Payment methods are evenly distributed, indicating no dependency on a specific payment option.
4. The most profitable brands are Mercedes, BMW, and Audi.
5. Market demand is stable with no significant decline.
6. Car purchases appear gender-neutral, with balanced customer distribution.
7. The largest sales contribution comes from customers aged 35–64.
8. The scatter plot indicates a pattern: the older the customer, the higher the car sale price tends to be.
9. There is a significant performance gap between top and bottom salespersons — suggesting a need for targeted training programs for low performers.
10. Many salespersons show negative profit, likely due to excessive discounting; this indicates the need for discount approval control.

Dataset:
https://www.kaggle.com/datasets/anjaliprajapati307/usa-car-sales-dataset-2018-2024?utm_source=chatgpt.com

Data Warehouse Star Schema Components:
fact_sales
dim_dates
dim_customers
dim_car
dim_salesperson
dim_region
dim_payments

Key steps in the ETL workflow include:
1. Standardizing date formats
2. Data cleaning and validation
3. Key mapping between fact and dimension tables

Power BI Dashboard Structure:
The dashboard is organized into three main pages:
1. Summary Overview
2. Customers and Market Analysis
3. Salesperson Performance

PBIX file:
The PBIX file is too large to upload directly to GitHub. Please download it from the following link:
https://drive.google.com/drive/folders/1_q9_pMhwO92h1Tqc5UVCqEXZsAy9BuZ2?usp=sharing
