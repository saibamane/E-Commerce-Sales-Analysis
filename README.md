### E-Commerce sales analysis

## Tableof Contents

- [Project overview](#project-overview)
- [Data sources](#data-sources)
- [Tools](#tools)
- [Data cleaning and preparation](#data-cleaning-and-preparation)
- [Exploring data analysis](#exploring-data-analysis)
- [All about dataset](#all-about-dataset)
- [Conclusion](#conclusion)

### Project overview

This data analysis project aims to provide insights into the sales Performance of an e-commerce company over the past year. By analyzing various aspects of the sales data, we seek to identify trends,makedata-driiven Recommendation, and again deeper understanding of the company Performance.

### Data sources

Sales data:The primary dataset used for this analysis is the "sales_data.csv" file, containing information about each sales made by the company.

### Tools

- Excel- Data cleaning [Download here](https://www.office.com/)
- SQL server -Data analysis
- Excel, Power BI, Tableau - Creating reports


### Data cleaning and preparation

In the initialdata preparation phase, we performed the following tasks:
- ## Null & Empty values:
      Check for Null records and replace them with correct strings or numeric values

- ## Unwanted special characters
      Use clean formula to correct the text

- ## Irrelevant columns
      Remover irrelevant columns using Ctrl - function
  
- ## Errors in spelling
      There are records in the category column that require us to replace Portuguese strings from the category_name with English-translated versions.

### Exploring data analysis
  - EDA involved exploring the sales data to answer the questions, such as:
    1. Weekday Vs Weekend (order_purchase_timestamp) Payment Statistics
    2. Number of Orders with review score 5 and payment type as credit card.
    3. Average number of days taken for order_delivered_customer_date for pet_shop
    4. Average price and payment values from customers of sao paulo city
    5. Relationship between shipping days (order_delivered_customer_date - order_purchase_timestamp) Vs review scores.


### All about dataset:
    Olist data is a Brazilian E-Commerce Public Dataset.
    The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil.
    This is real commercial data, it has been anonymized.
    Olist is the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those 
    merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners. The company emphasizes the structuring of 
    the product and focuses on service excellence for the tenants and the end consumers!

    EDA analysis
    1.## Weekday Vs Weekend (order_purchase_timestamp) Payment Statistics
    Most of the sales are done on weekdays. Major sales happened on Tuesdays and on the weekend it’s on Sundays. 
    The highest number of payments are made through Credit card mode. 
    As we check daywise payment statics then Friday is on top.
    
![KPI 1](https://github.com/saibamane/E-Commerce-Sales-Analysis/assets/154344179/dc5a23f3-6647-494b-a1ea-c1add479e9d5)

    2. ### Number of Orders with review score 5 and payment type as credit card.
    With a review score of 5 and payment type as a credit card, We received 44333 orders.
    More orders have been placed via credit card payment than boleto, voucher, and debit card.
    More than 70% of sales were paid by Credit Card which is the main payment method in the market. However, payment using Boleto has 
    slightly increased by 7% and a significant increase 
    in using a debit card has been founded.

![KPI 2](https://github.com/saibamane/E-Commerce-Sales-Analysis/assets/154344179/3a874273-f5e3-4762-9b23-fe60a215af7e)
   
    3.## Average number of days taken for order_delivered_customer_date for pet_shop
    21 days is the maximum avg days taken to deliver the order and for the product : (Office furniture).
    5 days is the minimum avg days taken to deliver the order and for the product: artes_e_artesanato (arts and craftmanship).
    Year wise sales are increasing which means we doing good in the market.

![KPI 3](https://github.com/saibamane/E-Commerce-Sales-Analysis/assets/154344179/78e45703-c5bb-4cf0-9f9f-945cd4e61593)
 
    4.## Average price and payment values from customers of sao paulo city
    Sao Paulo City – Avg price is 108 and avg payment is 153
    The total number of customers is nearly 100K. We found out that São Paulo (SP) contains the most customers and is 3 times more 
    than 
    the second one. It is expected São Paulo has, 
    particularly the most order payment value. Either Rio de Janerio (RJ) or Minas Gerais (MG) takes 10% of total customers. This 
    indicates that the top 5 states contribute 80% of total 
    customers.

![KPI4](https://github.com/saibamane/E-Commerce-Sales-Analysis/assets/154344179/5637736f-5995-4efa-be7b-f33eb251353c)
    
    5.## Relationship between shipping days (order_delivered_customer_date - order_purchase_timestamp) Vs review scores.
    11 avg shipping days taken for review score 5 & 20 avg shipping days taken for review score 1.
    We get positive/high ratings when delivery time is less and negative feedback from the customers when it takes long to deliver the 
    product.
    Lesser the delivery days – the higher the positive reviews.
    After analysing the review scores(customer satisfaction rating), the average score is 4.07/5, which shows positive satisfaction 
    with Olist’s services.

![KPI 5](https://github.com/saibamane/E-Commerce-Sales-Analysis/assets/154344179/a265e003-8956-4602-834b-4ba5a12f8301)

### Conclusion

The analysis also focuses on the product categories with respect to the price and the review score of the customer. So, if the company focuses on the product’s pricing strategy and makes product improvements on the basis of consumer opinion, the company can make better revenue and can increase the range of products under each category. 

The organization needs to purposely address the purchaser's survey and continue to adjust and change the item range. Future work in this space might incorporate recognizing how connections revealed in this investigation might be applied to further develop income inside comparative internet business organizations in Brazil

