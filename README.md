# **Olist-E-commerce-Data-Aanalysis**
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/3eabf4f0-8701-4970-82de-75978d1ffed7)
--

## **INTRODUCTION**
In April, I took part in a data challenge hosted by the Twitter data community. The challenge focused on analyzing a dataset from Olist, a well-known e-commerce company in Brazil. This dataset provided crucial details about various aspects of Olist's operations, such as product listings, sellers, and customer interactions. My objective was to explore the dataset and discover valuable insights based on specific questions. The challenge organizers meticulously curated and prepared the dataset to ensure that participants, including myself, could extract meaningful information and gain insights relevant to Olist's business.


## **THE GOALS OF THIS CHALLENEGE**
### This project challenge seeks to achieve the following goals :
- Validate and clean the data to improve accuracy and usability
- Analyze the data to address the problem statement
- Offer recommendations to Olist company
--

## **DATASET AND DATA DICTIONARY**
The Olist [dataset](https://drive.google.com/drive/folders/1re0HnJD5TCNVkVDHoPQ08aByKMWRRRJC) comprises nine separate datasets, all of which are stored in CSV format:
1. olist_order_items_dataset
2. olist_orders_dataset
3. olist_order_payments_dataset
4. olist_order_reviews_dataset
5. olist_products_dataset
6. olist_customers_dataset
7. olist_sellers_dataset
8. olist_geolocation_dataset
9. olist_category_dataset

The olist [Data Dictionary](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/files/11643097/Olist.Data.Dictionary.2.pdf) that offers a complete overview of the dataset. This data dictionary is a valuable reference as it provides in-depth explanations of each variable and its significance within the dataset. It serves as a useful tool for understanding and interpreting the data effectively.

## **CLEANING OF ALL THE TABLES**

With the messy table on the left-hand side and the cleaned table on the right-hand side, the cleaning process involved various steps to ensure the data was accurate and consistent. In the messy table, you could see inconsistencies, missing values, duplicates, and other issues that could potentially impact the analysis. However, after applying rigorous data cleaning techniques, the cleaned table now presents a more organized and reliable dataset. The cleaning process involved handling missing values by imputing or removing them, standardizing formats, correcting inconsistencies, removing duplicates, and addressing any other data quality issues. As a result, the cleaned table provides a solid foundation for conducting meaningful analysis and extracting valuable insights from the dataset.

### **CUSTOMER TABLE**
Messy                                                           | Cleaned
:--------------------------------------------------------------:|:---------------------------------------------------------------:
<img width="641" alt="dirty customer" src="https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/37d43bd9-e65e-479b-af0d-02c4c616688f"> | ![cleaned customer dataset](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/3fccb45c-8ba1-4162-b750-8bd6c06d5cdd)

### **GEOLOCATION TABLE**
Messy                                                           | Cleaned
:--------------------------------------------------------------:|:---------------------------------------------------------------:
<img width="584" alt="dirty geolocation" src="https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/53256ed4-73d8-4fc5-ac8a-6c695d876a1b"> | ![cleaned geo table](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/05b17632-bd35-4979-9057-2e41c770407a)

### **ORDER TABLE**
Messy                                                           | Cleaned
:--------------------------------------------------------------:|:---------------------------------------------------------------:
![dirty order dataset](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/1b3dc73f-d98f-44b9-bbcf-2a266e00ad8e) | ![cleaned order table](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/887d78e4-72cf-4432-a408-db9624ed63b9)

### **PRODUCT TABLE**
Messy                                                           | Cleaned
:--------------------------------------------------------------:|:---------------------------------------------------------------:
![DIRTY PRODUCT ID](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/dd929fa1-a3c2-46b7-b935-914120c690c7) | ![cleaned product table](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/e32f61e8-f707-41a5-b518-782c98fd5149)

### **PRODUCT CATEGORY TABLE**
Messy                                                           | Cleaned
:--------------------------------------------------------------:|:---------------------------------------------------------------:
![DIRTY PRODUCT CATEGORY](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/8b3057cd-7aa0-4d49-bea1-08b0f523a20b) | ![cleaned product category](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/41c31141-6361-43f2-a150-61d4c6973639)

### **ORDER ITEM TABLE**
Messy                                                           | Cleaned
:--------------------------------------------------------------:|:---------------------------------------------------------------:
![UNCLEANED OREDER ITEM ID](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/9fc64550-dd54-47da-8ed1-3341e80ec80b) | ![cleaned order item id](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/dc51a753-6103-4060-a32e-8d3a1a2cddff)

### **SELLER TABLE**
Messy                                                           | Cleaned
:--------------------------------------------------------------:|:---------------------------------------------------------------:
![DIRTY SELLER DATA](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/7c5e0d51-135b-47d5-a948-afe20a633bd1) | ![cleaned seller state](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/7cabd66c-dcdc-4fcf-8462-4e9286b1d7c2)

### **ORDER PAYMENT**
Messy                                                           | Cleaned
:--------------------------------------------------------------:|:---------------------------------------------------------------:
 <img width="664" alt="DIRTY PAYMENT ORDER" src="https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/36b97402-a45b-47ae-bcd3-5a1758c31a3e"> | ![cleaned payment order](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/fb2ac980-518b-4fce-a6a1-ada27fd44c6c)

## BUSINESS QUESTIONS
1. What is the total revenue generated by Olist, and how has it changed over time?
2. How many orders were placed on Olist, and how does this vary by month or season?
3. What are the most popular product categories on Olist, and how do their sales volumes compare to each other?
4. What is the average order value (AOV) on Olist, and how does this vary by product category or payment method?
5. How many sellers are active on Olist, and how does this number change over time?
6. What is the distribution of seller ratings on Olist, and how does this impact sales performance?
7. How many customers have made repeated purchases on Olist, and what percentage of total sales do they account for?
8. What is the average customer rating for products sold on Olist, and how does this impact sales performance?
9. What is the average order cancellation rate on Olist, and how does this impact seller performance?
10. What are the top-selling products on Olist, and how have their sales trends changed over time?
11. Which payment methods are most commonly used by Olist customers, and how does this vary by product category or geographic region?
12. How do customer reviews and ratings affect sales and product performance on Olist?
13. Which product categories have the highest profit margins on Olist, and how can the company increase profitability across different categories?
14. Geolocation having high customer density. Calculate customer retention rate according to geolocations.

## ANSWERS TO THE BUSINESS QUESTIONS
### 1) What is the total revenue generated by Olist, and how has it changed over time?
![revenue by quarter](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/002dfdb1-18ce-4d8e-9dc3-4c478942ecce)

The total revenue generated by Olist was approximately R$15.9 million. The quarter with the highest revenue was the second quarter of 2018, while the lowest revenue was generated in the third quarter of 2016, with revenues of approximately R$3.3 million and R$136.23, respectively.

### 2) How many orders were placed on Olist, and how does this vary by month or season?
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/edb999c4-3ff8-4402-80de-67d5b53356cc)

The total number of orders placed on Olist was 98,207. In January 2017, Olist received the highest number of orders, with approximately 7,423 orders. The lowest number of orders occurred in September 2018 and December 2016, with only one order each.

### 3) What are the most popular product categories on Olist, and how do their sales volumes compare to each other?
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/52732086-4ed1-48f5-926e-0970dcb03e7a)

The most popular product category on Olist is "bed bath table," and as we examine the popularity from the most to the least popular categories, we observe a significant decrease in their sales volume. This decrease in sales volume from the most popular to the least popular categories suggests certain implications.

### 4) What is the average order value (AOV) on Olist, and how does this vary by product category or payment method?
by payment method                                                          | by product category
:--------------------------------------------------------------:|:---------------------------------------------------------------:
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/90831331-a361-4d40-9e89-9fe612d9a6c5) | ![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/7e0f9813-e31a-48b0-acad-1f99e6b40c4a)


The average order value (AOV) across all payment methods on Olist is approximately R$153.44. When categorizing by payment method, voucher payments had the lowest AOV of R$62.33, while credit card payments had the highest AOV of R$162.70. Furthermore, when categorizing by product category, computers had the highest AOV, followed by fixed telephony.

### 5) How many sellers are active on Olist, and how does this number change over time?
Active sellers                                                        | Active sellers
:--------------------------------------------------------------:|:---------------------------------------------------------------:
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/5c52bb7c-cdf5-4626-b4d9-5443b56a5074) | ![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/37466b45-c22d-44ef-a700-a6669e388f23)

Olist had a total of 4,312 active sellers. The highest number of active sellers was in 2018 with 2,833, followed by 1,784 in 2017 and the lowest number of active sellers was 145 in 2016. On a quarterly basis, Olist experienced an increase in active sellers throughout most quarters, except for a decline in the last quarter of 2018 (Q3) where it had 52 sellers fewer compared to the previous quarter (Q2), with 1,680 sellers in Q2 and 1,628 sellers in Q3.

### 6)  What is the distribution of seller ratings on Olist, and how does this impact sales performance?
Distribution of sellers                                                       | Correlation co-effecient
:--------------------------------------------------------------:|:---------------------------------------------------------------:
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/ebba1572-a642-40bf-bbae-a62d89ca48c0) | ![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/567f0e17-61ac-4726-b6b7-609229d52663)

It can be concluded that sellers with review scores of 4 and 5 had the highest number of orders, indicating positive sales performance. Furthermore, sellers with higher review scores also generated higher total revenue, suggesting a correlation between positive reviews and increased sales. However, it is interesting to note that sellers with a review score of 1 had the highest average revenue, indicating that other factors may influence sales performance beyond just review scores.

### 7)  How many customers have made repeated purchases on Olist, and what percentage of total sales do they account for?
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/521be6ee-f66b-41aa-9262-2cfb6d743177)

Out of the 96,096 customers in Olist, a small fraction of 2,997 customers have made repeat purchases, implying a low customer retention rate. The majority of customers (93,099) have only made a single purchase and have not returned for additional purchases. Moreover, the sales generated by repeat customers account for only 13% of the total sales.

### 8) What is the average customer rating for products sold on Olist, and how does this impact sales performance?
Average rating                                                    | Impact on Sales performance
:--------------------------------------------------------------:|:---------------------------------------------------------------:
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/5623dc74-9d4b-4d27-97da-4c8af12c59d1) | ![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/7a6f163b-a54f-4eec-867a-f5f59f60bebe)

The average rating on Olist is 4, indicating a positive impact on sales performance. This high average rating suggests that customers are generally satisfied with their purchases, which can lead to increased customer trust, loyalty, and higher sales. The positive word-of-mouth recommendations from satisfied customers may also attract new customers, further contributing to revenue growth. Additionally, products with higher average ratings are likely to be perceived as reliable and of good quality, increasing their desirability and potentially driving higher sales volumes.

### 9) What is the average order cancellation rate on Olist, and how does this impact seller performance?
Cancellation rate                                              | Effect on Sales performance
:--------------------------------------------------------------:|:---------------------------------------------------------------:
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/61fc854c-4300-4190-9a66-2fdfb181427c) | ![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/cf495a0c-26b5-48f2-b66a-347fa6f615af)

Olist's cancellation rate of 0.48 suggests a low percentage of order cancellations, indicating that the majority of customers complete their purchases. This positive trend can be seen as a favorable sign for Olist's sales performance, indicating that customers are content with their buying decisions and have trust in the products and services provided by Olist.

### 10) What are the top-selling products on Olist, and how have their sales trends changed over time?
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/5cf321cf-9ff1-4102-9840-dd9baf944ffb)

Computer accessories reign supreme as the best-selling items on Olist, closely followed by health and beauty products, watches and gifts, bed and bath essentials, and sport and leisure items.

### 11) Which payment methods are most commonly used by Olist customers, and how does this vary by product category or geographic region?
Number of orders with each payment methods                                          | Payment method by geographical location
:--------------------------------------------------------------:|:---------------------------------------------------------------:
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/63f901f1-c898-4fff-b113-04bc3599b2c3) | ![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/bf851ed5-9840-459d-89ed-3f45c727f6ee)

Credit card was used for 76505 orders, making it the most common payment method. Boleto followed with approximately 19784 orders, while voucher and debit card were used for around 3866 and 1528 orders, respectively. In São Paulo, "Health Beauty" products were purchased 71 times using debit card as the payment method. Additionally, "Bed Bath Table" and "Health Beauty" were popular product categories paid for with credit cards. In Minas Gerais, credit card payments were mainly associated with "Health Beauty" products, in São Paulo, voucher payments were most commonly associated with auto products, while boleto payments were used for "Bed Bath Table" products. Credit cards were frequently used for "Computer Accessories" and "Health Beauty" products.

### 12) How do customer reviews and ratings affect sales and product performance on Olist?
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/7a9ad038-5494-4a19-a95c-71b043431683)

Excellent! which has a 5-star rating, received approximately 56,902 reviews. Out of the total purchases of 23,220 products , a significant number, 5-star ratings were given. On average, each product in the generated a revenue of R$160.78. Interestingly, as we move down the rating score, the revenue decreases. This observation implies that Olist may have pricing issues that need to be addressed in order to adjust and optimize revenue.

### 13)  Which product categories have the highest profit margins on Olist, and how can the company increase profitability across different categories?
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/649bd0b8-4a66-4c17-952b-6c447394656e)

The profit margins across different product categories vary significantly. The highest profit margin is observed in the "Fixed telephony" category with a percentage profit margin of 327.78, followed by "Signaling and security" (287.02) and "Drinks" (286.87). On the other hand, categories like "Furniture mattress and upholstery" (88.63) and "Home appliances 2" (91.01) have relatively lower profit margins.

### 14)  Geolocation having high customer density. Calculate customer retention rate according to geolocations.
![image](https://github.com/tolamoye/Olist-E-commerce-Data-Aanalysis/assets/128150171/32ee15d1-9e64-47da-bbc8-d42f74aeed10)

Geolocations with higher customer densities indicate areas where the company has a larger customer base and potentially higher market demand. Geolocations with relatively higher customer densities include Acre (4.94%), Rondonia (4.35%), Mato Grosso (3.42%), Rio de Janeiro (3.34%), and Goias (3.27%).  The customer retention rate is a measure of the percentage of customers who make repeated purchases. It provides insights into customer loyalty and the effectiveness of the company's strategies to retain customers.
