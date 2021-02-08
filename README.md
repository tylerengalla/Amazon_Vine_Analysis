# Amazon_Vine_Analysis

## Overview 
Create a Postgres instance on top of AWS and load Amazon reviews wrriten by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. 

Then use PySpark to perform ETL process to extract the dataset, transform the data, connect to our AWS RDS instance, and load the transformed data into pgAdmin. 

Finally, use PySPark to determine if there is any bias toward favorable reviews from Vine members in the data. 

## Results 

### Vine Reviews (paid)
![](/images/total_paid.png)

### Non-Vine Reviews (unpaid)
![](/images/total_unpaid.png)

### Vine 5-Star Reviews 
![](/images/paid_5.png)

### Non-Vine 5-Star Reviews
![](/images/unpaid_5.png)

### Percentage of Vine reviews that were 5-Stars
![](/images/paid_percentage.png)

### Percentage of Non-Vine reviews that were 5-Stars
![](/images/unpaid_percentage.png)

## Summary 
