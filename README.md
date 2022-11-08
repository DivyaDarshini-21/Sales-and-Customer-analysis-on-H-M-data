# Sales-and-Customer-analysis-on-H&M data

In the dataset..... the purchase history of customers across time, along with supporting metadata is provided. 

Your challenge is to predict......... what articles each customer will purchase in the 7-day period immediately after the training data ends. 

Customer who did not make any purchase during that time are excluded from the scoring.

Files

articles.csv - detailed metadata for each article_id available for purchase

customers.csv - metadata for each customer_id in dataset

transactions_train.csv - the training data, consisting of the purchases each customer for each date, as well as additional information. 
Duplicate rows correspond to multiple purchases of the same item.
Your task is to predict the article_ids each customer will purchase during the 7-day period immediately after the training data period
