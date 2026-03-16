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

--------------------------


### Customer & Sales Details

This page provides an overview of customer activity, service performance, and key targets.

**Visualizations**: `Customer Details (Total Customers, Returning Customers, Top Customer Overview, Top 10 Customers Overview, Top States by Customers)`, `Service Details (Average Delivery Days, Average Est. Delivery Deviation, Average Review Score)`, `Targets (Total Customers, Late Deliveries)`

![](./Demos/2.%20Customer%20&%20Service%20Details.gif)

#### Business Questions and Insights

1. How strong is customer retention on the platform?
> The platform has a large customer base, but the returning customer rate is quite low, suggesting most customers make one-time purchases.

2. Is revenue driven by high-value purchases or frequent buyers?
> Customer spending varies widely, but high revenue mostly comes from single high-value purchases.

3. Where are most of the customers located geographically?
> Most customers are concentrated in major Brazilian economic regions, especially São Paulo.

4. Are the delivery expectations met?
> Orders are often delivered earlier than expected, reflecting efficient logistics operations.
> Although delivery is generally efficient, some orders still arrive late.

--------------------------


### Product Details

This page provides an overview of product performance and ordering trends.

**Visualizations**: `Most Ordered Product Categories`, `Most Expensive Product Categories`, 'Metric Trending (Metrics: Completed Orders, Customers, Late Deliveries, Orders, Revenue)`

![](./Demos/3.%20Product%20Details.gif)

#### Business Questions and Insights

1. Which product categories have the highest average selling price?
> Watches & Gifts are premium products with the highest unit value.

2. Which categories generate high revenue through both price and demand?
> Health & Beauty performs well in both price and demand, making it a high-revenue category.

3. Which categories rely on high sales volume rather than high price?
> Bed Bath Table has high order volume but lower average price.

--------------------------


### Map

This page provides a map visualizating key metrics `Completed Orders`, `Customers`, `Late Deliveries`, `Orders`, `Revenue`.

![](./Demos/4.%20Map.gif)

#### Business Questions and Insights

1. Which region generates the highest revenue?
> The Southeast region of Brazil generates the highest revenue, significantly outperforming other regions. States such as São Paulo, Rio de Janeiro, Minas Gerais, and Espírito Santo show the largest concentration of revenue. This indicates that customer demand, purchasing power, and order volume are strongest in this region, making it the primary driver of overall business performance.

2. Which state is the company’s strongest market?
> São Paulo is the company’s strongest market and significantly outperforms all other states. This highlights São Paulo as the core market where the company generates a substantial portion of its revenue.

3. Which regions show stable but moderate performance?
> The southern region of Brazil, particularly states such as Paraná and Rio Grande do Sul, shows stable but moderate performance. These states have consistent levels of activity and revenue but do not reach the same scale as the Southeast. This suggests that the region represents a reliable secondary market with steady demand.

4. Which regions present potential opportunities for growth?
> The Northeast and Central regions of Brazil present strong opportunities for future growth. States such as Bahia, Ceará, Goiás, and the Federal District show moderate activity.

5. Which region currently has the lowest market penetration?
> The Northern region of Brazil shows the lowest market penetration. States such as Amazonas and neighboring northern areas have relatively small revenue markers compared to other parts of the country.

--------------------------


### Tooltips

The bellow pages include helpful tooltips used in selected visuals in the dashboard. 

#### Category

![](./Demos/5.%20Category%20Tooltip.PNG)


#### Orders

![](./Demos/6.%20Orders%20Tooltip.PNG)


#### Review Score

![](./Demos/7.%20Review%20Score%20Tooltip.PNG)

--------------------------


### Colorset

This page provides the hex codes of the colours used in the dashboard.

![](./Demos/8.%20Colour%20Sets.PNG)
