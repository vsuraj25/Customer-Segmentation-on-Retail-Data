# Customer-Segmentation-on-Retail-Data
* About - This is a customer segmentation projects which aims to predict on which cluster the customer belongs depending on the spendings and other entities.
* Problem statement -  Using unsupervised learning, divide the customers using diffrent clusters by analysing the behaviour, spending and other entities of a customer purchase.
* Appraoch - RFM Analysis :- The “RFM” in RFM analysis stands for recency, frequency and monetary value. RFM analysis is a way to use data based on existing customer behavior to predict how a new customer is likely to act in the future. An RFM model is built using three key factors:

- how recently a customer has transacted with a brand
- how frequently they’ve engaged with a brand
- how much money they’ve spent on a brand’s products and services

After getting these important insights,  we used the kmeans clustering algorithm for creating cluster based on the monetary, recency and frequency values.

* Conclusion - Using the wlobow mwnthod, we came to know that 3 as the value of k is the best cluster distribution for our data. Here is the analysis of clusters : 
- Cluster 0 - Rare Customers, low purchase frequency and minimal spending
- Cluster 1 - Frequent Customers, high purchase frequency and highest spending
- Cluster 2 - Frequent Customers, low purchase frequency and less spending
