# Amazon_Vine_Analysis
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Analysis Overview

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for wireless user.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Results

-  **Below results are showing Vine reviews and non-Vine reviews.**  

![image](https://user-images.githubusercontent.com/107137215/194112527-bfab6800-4444-4f6b-972d-97ed145d48c0.png)

![image](https://user-images.githubusercontent.com/107137215/194112792-6a2d6076-833f-444c-9d11-b28e765fdb71.png)

- **Below are the results of Vine reviews were 5 stars and non-Vine reviews were 5 stars**

![image](https://user-images.githubusercontent.com/107137215/194112604-15a0a0a3-6b8e-4e3e-a2d6-2b36143237ef.png)

![image](https://user-images.githubusercontent.com/107137215/194112946-9484f216-fa10-4d0e-810b-98cd64e3a668.png)

- **Below are the results of percentage of Vine reviews were 5 stars and  percentage of non-Vine reviews were 5 stars?** 

![image](https://user-images.githubusercontent.com/107137215/194112677-6ec45218-7300-4c20-b6d1-b977ff584d2c.png)

![image](https://user-images.githubusercontent.com/107137215/194113192-11a973e8-d747-4718-9d83-e1a373bc8f94.png)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Summary

36% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is 47%. This describes a negative bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.



