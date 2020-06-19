# E-Commerce-Customer-Segmentation
### Objective : 
Explore and identify different segments present in the customer transaction data.
### Input Data :
The data has been taken from the e commerce dataset on [Kaggle](https://www.kaggle.com/carrie1/ecommerce-data) that consists of transactions from 2010 to 2011. 
### Description :
1.	Data cleaning is performed to handle negative values and null values.
2.	EDA is carried out to explore the dataset and identify the characteristics of the data.
3.	RFM Analysis: 
RFM (Recency, Frequency, Monetary) analysis is a customer segmentation technique that uses past purchase behavior to divide customers into groups. We will create those 3 customer attributes for each customer.
4.	Customer Segments with RFM Model:
I have made use of quartiles to create customers segments from RFM Model. A score from 1 to 4 is assigned to Recency, Frequency and Monetary. Four is the best/highest value, and one is the lowest/worst value. A final RFM score is calculated simply by combining individual RFM score numbers. Based on these scores segments of customers are created. 

