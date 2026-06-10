# ${\color{blue}\text{Brazilian E-Commerce Analytics Dashboard}}$

This project analyzes over 100,000 e-commerce orders from the Olist marketplace in Brazil using Power BI. The objective was to identify sales trends, customer behavior patterns, product performance, and delivery efficiency through interactive dashboards and business-focused KPIs.

#

### Tools
- Power BI
- DAX
- Data Modeling
- Power Query

#

### Dataset

This project uses the Olist Brazilian E-Commerce Dataset, which contains approximately 100,000 orders placed between 2016 and 2018 across multiple marketplaces in Brazil.

The dataset includes information about:

- Orders
- Customers
- Products
- Sellers
- Payments
- Reviews
- Geolocation data

The data was modeled into a relational schema in Power BI and used to analyze sales performance, customer satisfaction, and logistics operations.

**Source**: Olist Brazilian E-Commerce Dataset on Kaggle

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

#

### Data Model

The dashboard was built using a star-schema-inspired model with:

**Fact Tables**

- Order Items
- Order Payments
- Orders

**Dimension Tables**

- Customers
- Products
- Sellers
- Reviews
- Calendar
- Brazilian States (lookup table)
- Product Names in English

<img width="1946" height="1070" alt="image" src="https://github.com/user-attachments/assets/59b9da63-7ea1-4db6-9309-334571079459" />

<br></br>
Key relationships were created to support time-series analysis, customer segmentation, product analysis, and operational metrics.

#

### Dashboard Pages
**Sales Overview**
- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Revenue Trends
- Top Product Categories
- Revenue by State
- Payment Method Distribution

<img width="1785" height="1006" alt="image" src="https://github.com/user-attachments/assets/1fd2538c-52c8-4426-b077-c35d10f3f98e" />



**Customer & Operations**
- Review Score Distribution
- Average Delivery Time
- Late Delivery Rate
- Customer Geography
- Delivery Performance vs Customer Satisfaction

<img width="1785" height="1007" alt="image" src="https://github.com/user-attachments/assets/2d8e88c9-e648-4e00-88fb-a11bf3254f33" />


#

### Key Insights
- Customer satisfaction decreases significantly when deliveries are delayed.
- A small number of states account for the majority of customers and revenue.
- Product categories contribute unevenly to total revenue, highlighting key growth areas.
- Most customer reviews are highly positive, with 5-star ratings representing the largest share of feedback.
