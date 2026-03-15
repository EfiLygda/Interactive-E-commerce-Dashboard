# Interactive E-commerce Dashboard in Power BI

This project presents an interactive Power BI dashboard built using the Brazilian e-commerce Olist dataset. The goal of the dashboard is to analyze sales performance, customer behavior and delivery efficiency.

The dashboard enables stakeholders to explore key business metrics such as revenue, order volume, customer satisfaction, and logistics performance through interactive visualizations.

![](./Demos/9.%20Demo.gif)


## Tools Used

The tools used in this project include: `Power BI`, `DAX (Data Analysis Expressions)`, `Data modeling`, `Data visualization`

## Dataset 

The dataset contains information about: `customers`, `orders`, `payments`, `products`, `sellers`, `reviews`, `geolocation`, `leads`

The available tables are connected to analyze the full e-commerce process from purchase to delivery and customer feedback.

![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F2473556%2F23a7d4d8cd99e36e32e57303eb804fff%2Fdb-schema.png?generation=1714391550829633&alt=media)

> [!NOTE] 
> This repository uses the data available at [Kaggle](https://www.kaggle.com/datasets/terencicp/e-commerce-dataset-by-olist-as-an-sqlite-database).


## Dashboard Pages

### Summary

This page provides a high-level summary of business performance, in order to quickly understand overall company performance and sales growth over time.

**Visualizations**: `Overall Business Performance (Total Revenue, Total Customers, Total Orders, Cancellation Rate)`, `Revenue Trending`, `Order Fulfillment', `Average Review Score`, `Most Profitable Product Categories`, `Most Profitable States`

![](./Demos/1.%20Summary%20Tab.gif)

#### Business Questions and Insights

1. What is the total revenue and number of orders over time? Is the platform growing over time?

> **Total Revenue**: $15.6M
> **Total Orders**: 99.44K
> The marketplace experienced consistent growth, suggesting increasing customer demand and platform adoption.
> Although, a sharp drop is noted due to incomplete data for the latest month (Sept 2018).

2. How successful are orders from placement to completion?

> Approximately 98% of orders are completed, showing very high operational efficiency.

3. How satisfied are customers based on review ratings?

> **Average Review Score**: 4.09 / 5
> Customers generally report positive experiences.

4. Which product categories generate the most revenue?

> Lifestyle (`Health & Beauty`, `Bed, Bath & Table`, `Sports & Leisure`) and personal products (`Watches & Gifts`, `Computers & Accessories`) dominate revenue, suggesting consumer demand in everyday-use categories.

5. Which regions generate the most revenue?

> Sales are heavily concentrated in Brazil’s most economically active states, especially São Paulo.



### Customer & Sales Details

This page provides a high-level summary of business performance, in order to quickly understand overall company performance and sales growth over time.

![](./Demos/2.%20Customer%20&%20Service%20Details.gif)


### Product Details

![](./Demos/3.%20Product%20Details.gif)


### Map

![](./Demos/4.%20Map.gif)

### Tooltips

#### Category

![](./Demos/5.%20Category%20Tooltip.PNG)


#### Orders

![](./Demos/6.%20Orders%20Tooltip.PNG)


#### Review Score

![](./Demos/7.%20Review%20Score%20Tooltip.PNG)

### Colorset

![](./Demos/8.%20Colour%20Sets.PNG)
