# <p align = 'center'>Customer-Segmentation-with-K-means-Clustering and PCA</p>

## Dataset description
The Dataset summarizes the behavior of 8950 credit card holders during the last 6 months and consists of 18 features.

| Id      | Features | Description |
| ----------- | ----------- | ----------- |
|1 |Cust_Id:|	Identification of credit card holder|
|2 |Balance:|	A credit card balance or Total amount left in their account to make purchases|
|3 |Balance_Frequency:|	How frequently the balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)|
|4 |Purchases:|	Total amount of purchases made from account|
|5 |One_Off_Purchases:|	Maximum purchase amount done in one-go|
|6 |Installments_Purchases:|	Amount of purchase done in installment|
|7 |Cash_Advance:	|Cash in advance given by the user|

## The objective of analysis
This type of data set requires customer segmentation to comprehend the customers beheviour in order to help the client which is a credit card company.

## Conclusion
- In this project, I applied K-Means clustering, PCA, and K-Means clustering using PCA.
- In K-means I came up with 3 clusters.
- In PCA I came up with 8 dimension.
- In K-means clustering using PCA, I used 8 components, and came up with 3 clusters.
- The result of K-Means clustering using PCA is the same as K-Means clustering. So, I did not repeat them.

After performing the models, the customers are segmented into 3 groups:
- Group 0: These group of customers are not spenders.
- Group 1: These group of customers are unable to spend much as their balance is low
- Group 2: These group of customers are spenders.

The credit card company, can use these informations to define a marketing strategy. People in Group 2 clearly have the capacity to spend their money. Therefore, the company can use their spending habits to optimize the strategies to get them to spend even more.
