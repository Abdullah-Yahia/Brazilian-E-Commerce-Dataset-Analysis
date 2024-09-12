# Brazilian-E-commerce-Dataset-Analysis

Welcome to the Brazilian E-Commerce Public Dataset by Olist. This dataset contains information on 100,000 orders placed at the Olist Store in Brazil. The data covers orders made from 2016 to 2018 through various marketplaces. It provides a comprehensive view of each order, including order status, pricing, payment and shipping performance, customer location, product details, and reviews written by customers.

In addition to the main dataset, we have also made available a geolocation dataset that correlates Brazilian zip codes with latitude and longitude coordinates.

Please note that this dataset is real commercial data, but it has been anonymized to protect privacy. Any references to the companies and partners in the review text have been replaced with the names of Game of Thrones great houses for confidentiality.
![](https://github.com/Abdullah-Yahia/Brazilian-E-Commerce-Dataset-Analysis/blob/main/Olist.png)
# Dataset Details

- **Number of Orders:** 100,000
- **Data Range:** 2016 to 2018
- **Marketplace:** Multiple marketplaces in Brazil
- **Data Anonymization:** Yes

## Basic Analysis
 - Focus on  `orders`, `customers`, `payments`, `products` and `reviews` datasets.  
    * Analysis by Purchase Period
    * Analysis by Customer State
    * Analysis by Payment Type
    * Analysis by Product Categories
    * Analysis by Review Score

## Project Workflow

1. **Data Wrangling**
    
   The first step of the project is to clean and prepare the data for analysis. The data wrangling process includes:

   - Handling missing values
   - Handling duplicate values
   - Handling incorrect data types
   - Handling outliers
   - Handling inconsistent data
   - Handling data redundancy
   - Handling data normalization

2. **Exploratory Data Anlaysis**

    The second step of the project is to explore the data and extract meaningful insights. The exploratory data analysis process includes:
    
    - Order Analysis
    - Product Analysis
    - Payment Analysis
    - Customer Analysis
    - Reviews Analysis
    - Sellers Analysis

3. **Data Visualization**
   
    The third step of the project is to visualize the data and extract meaningful insights. The data visualization process includes:
    
    - Product Category with most outstanding reviews given by customers
    - Visualize OTD(On Time Delivery) rate of orders
    - Visualize the demographics of customers
    - Visualize the frequency of purchases made by customers
    - Visualize the monetary value of purchases made by customers
    - Visualize the recent purchases made by customers
    - Visualize the customers segmentation based on RFM analysis
  
4. **Dashboard**

    The last step of the project is to create a dashboard that can be used to visualize the data and extract meaningful insights. The dashboard includes:
    
    - Product Category sales performance
    - Daily sales performance

## 🗂️ Entity Relationship Diagram

![ERD](https://github.com/Abdullah-Yahia/Brazilian-E-Commerce-Dataset-Analysis/blob/main/SSRS%26SSAS/screenshots/ERD.png)

The Entity Relationship Diagram (ERD) provides a comprehensive graphical view of the logical structure of our database. It helps to understand how different tables are related to each other in the database.


The diagram includes the following tables:

- `customers_dataset`: This dataset has information about the customer and its location. Use it to identify unique customers in the orders dataset and to find the orders delivery location.
  
- `geolocation_dataset`: This dataset has information Brazilian zip codes and its lat/lng coordinates.
  
- `orders_dataset`: This is the core dataset of the project.
  
- `order_items_dataset`: This dataset includes data about the items purchased within each order.
  
- `order_payments_dataset`: This dataset includes data about the orders payment options.
  
- `order_reviews_dataset`: This dataset includes data about the reviews made by the customers.
  
- `products_dataset`: This dataset includes data about the products sold by Olist.
  
- `product_category_name_translation`: This dataset translates the product_category_name to english.
  
- `sellers_dataset`: This dataset includes data about the sellers that fulfilled orders made at Olist.

Each table is linked to one or more other tables through foreign keys, representing the relationships between different entities in the e-commerce business model.



**Thank you for reading! 🙏**

<div align='center'><img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="1000"></div>
