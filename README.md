# online-business-analysis-using-power-BI
Power BI Project

**Data**
•	Online shop to sell furniture, office supplies and technology 
•	Order table data, customers table data and products data 
The goal of the project is leveraging data analysis to gain insights into the performance of the online retail business, enhance decision-making, and identify opportunities for growth and improvement.

**Data Transformation**
•	data was clean and all primary keys is unique 
•	Add columns and measures: add Total revenue without profit and Total revenue with Profit, add month and year columns.

**Data Modeling**
•	One-to-many relationship with customer and order 
•	Made a lookup table for orders and products (order-product table) then add one-to-many relationship form product to (order-product) and from order to (order-product) 

**Sales Performance Analysis:** Understand Profit and Loss during last 4 years.
•	Add page navigation
•	Add sales key matrices: (Total Sales Revenue, Total Profit, Number of Orders, Total numbers of quantity)
•	Add slicers for years and months 
•	Visual revenue with profit by months, pie chart for shipping type, KPI for profit by year > 10% of revenue (make measure for 10% of revenue) and line chart for profit with shipping type 

**Customers Analysis:** Know the Top customer for years and months and how give us loss or profit and understand the data to answer (how can I give a discount for customers and make more customers in cities and states?)
•	Add slicer for customer segment types (Consumer, Corporator, Home office)
•	Add another key matrix for customers (Total customers.)
•	Make a tooltip page for shipping mode with profit, cards for (quantity, profit and discount) for all charts in customer page 
•	Visual for top 10 customer name vs (quantity and Profit) (Top customer with high profit)
•	Visual for 6 top states (pie chart)
•	Visual for customer segment (pie chart)

**Product analysis:** understand the inventory (quantity with orders)
•	Add slicer for product categories types (furniture, office supplies and technology)
•	Add another key matrix for product (Total products, Top selling product name)
•	Visual for sub-categories with orders count with legend of category (top sub-category was Binders and papers from office supplies category)
•	Visual Top 10 Product name with quantity of ordered
•	Visual Top and bottom 5 sub-category in the inventory based on products quantity (pie chart)

