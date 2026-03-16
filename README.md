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


## Business Questions & Insights

### Platform Growth & Sales Performance

1. How is the platform performing over time?
> **Total Revenue**: $15.6M
> **Total Orders**: 99.44K
> The marketplace shows consistent growth over time, indicating increasing customer demand and strong platform adoption. A noticeable drop in the final month (September 2018) appears due to incomplete data rather than an actual decline in sales.

2. Is revenue driven by high-value purchases or frequent buyers?
> Customer spending varies significantly, but overall revenue is largely driven by single high-value purchases rather than frequent repeat purchases.

### Order Fulfillment & Customer Satisfaction
1. How successful are orders from placement to completion?
> Approximately 98% of orders are successfully completed, indicating very high operational efficiency across the order processing pipeline.

2. Are delivery expectations met?
> Orders are often delivered earlier than the estimated delivery date, reflecting strong logistics performance.
> However, a small number of orders still arrive late, suggesting minor areas for improvement in delivery reliability.

3. How satisfied are customers?
> Average Review Score: 4.09 / 5
> Customer feedback is largely positive, indicating a generally high level of satisfaction with the purchasing experience.

### Customer Behavior & Retention
1. How strong is customer retention?
> Although the platform has a large customer base, the returning customer rate is relatively low.
> This suggests that most customers make one-time purchases, highlighting an opportunity to improve retention through loyalty programs or targeted marketing.

2. Where are most customers located?
> Customers are heavily concentrated in major Brazilian economic regions, particularly São Paulo, reflecting stronger purchasing power and higher online shopping activity.

### Product & Category Performance
1. Which product categories generate the most revenue?
> Lifestyle-related categories such as Health & Beauty, Bed Bath Table, and Sports & Leisure, along with personal product categories like Watches & Gifts and Computers & Accessories, generate the largest share of revenue.
These categories reflect strong consumer demand for everyday-use and personal products.

2. Which categories have the highest average selling price?
> Watches & Gifts have the highest average selling price, positioning them as premium products within the marketplace.

3. Which categories generate high revenue through both price and demand?
> Health & Beauty performs strongly across both average price and sales demand, making it one of the platform’s most profitable categories.

4. Which categories rely on high volume rather than high price?
> Bed Bath Table generates significant revenue through high order volume despite relatively low average prices, indicating strong mass-market appeal.

### Geographic Market Performance
1. Which region generates the highest revenue?
> The Southeast region of Brazil generates the largest share of revenue, significantly outperforming all other regions.
> States such as São Paulo, Rio de Janeiro, Minas Gerais, and Espírito Santo account for the majority of sales, highlighting the region as the primary driver of business performance.

2. Which state is the strongest market?
> São Paulo is the company’s most important market, clearly outperforming all other states in both revenue and customer concentration.

3. Which regions show stable but moderate performance?
> The Southern region, particularly Paraná and Rio Grande do Sul, shows stable but moderate performance.
> These states represent reliable secondary markets with steady demand, although they do not match the scale of the Southeast.

4. Which regions present growth opportunities?
> The Northeast and Central regions show strong potential for expansion.
> States such as Bahia, Ceará, Goiás, and the Federal District already demonstrate moderate activity, suggesting opportunities for targeted growth strategies.

5. Which region has the lowest market penetration?
> The Northern region of Brazil currently has the lowest market penetration.
> States such as Amazonas show relatively low revenue compared to the rest of the country, indicating untapped market potential.




## Dashboard Pages

### Summary

This page provides a high-level summary of business performance, in order to quickly understand overall company performance and sales growth over time.

**Visualizations**: `Overall Business Performance (Total Revenue, Total Customers, Total Orders, Cancellation Rate)`, `Revenue Trending`, `Order Fulfillment', `Average Review Score`, `Most Profitable Product Categories`, `Most Profitable States`

![](./Demos/1.%20Summary%20Tab.gif)

<!--  #### Business Questions and Insights

2. How successful are orders from placement to completion?

> Approximately 98% of orders are completed, showing very high operational efficiency.

3. How satisfied are customers based on review ratings?

> **Average Review Score**: 4.09 / 5
> Customers generally report positive experiences.

4. Which product categories generate the most revenue?

> Lifestyle (`Health & Beauty`, `Bed, Bath & Table`, `Sports & Leisure`) and personal products (`Watches & Gifts`, `Computers & Accessories`) dominate revenue, suggesting consumer demand in everyday-use categories.

5. Which regions generate the most revenue?

> Sales are heavily concentrated in Brazil’s most economically active states, especially São Paulo.
-->

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
