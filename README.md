# Amazon_Vine_Analysis
The purpose was to determine Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders..


Results: Using bulleted lists and images of DataFrames as support, address the following questions:

How many Vine reviews and non-Vine reviews were there?
![image](https://user-images.githubusercontent.com/93456209/156956873-1ab9e06c-4d68-4969-a91f-47b9cd952ce1.png)

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
![image](https://user-images.githubusercontent.com/93456209/156956436-4970461a-6b5b-456b-a71f-844afa653853.png)


What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![image](https://user-images.githubusercontent.com/93456209/156956557-8e256fd5-6ba1-41c8-b74f-bd46259b319e.png)



Summary: 
When comparing the percentage of reviews that were 5 stars from Amazon Vine members and non-Vine members, it can be concluded that there is no positive bias for reviews of Office Products in the Vine program.
