# Amazon Vine Analysis

## Background:
Amazon Vine Program is a service that allows manufacturers and publishers to receive reviews for their products. 
I picked electronics products from their 50 datasets and used PySpark to perform the ETL process to extract the dataset, transform the data,
connect to an AWS RDS instance, and load the transformed data into pgAdmin. 

### Technologies Used:
  - Amazon Reviews Data
  - PySpark
  - Google Colab
  - Amazon AWS
    - S3
    - RDS with PostgreSQL
  - pgAdmin

## Purpose of this analysis:
Analyze/compare Amazon reviews written by members of the paid Amazon Vine Program versus members who are not part of the Vine Program

## Results:
- Total number of reviews 

![num_reviews](Resources/num_reviews.png)


- Number of 5-star reviews

![5star_reviews](Resources/5star_reviews.png)


- Percentages of 4-star reviews

![percentage](Resources/percentage.png)

## Summary
#### Vine reviews of the dataset for "electronics" category on Amazon

![paidvsunpaid](Resources/paidvsunpaid.png)

The percentages of 5-star reviews cannot really tell us if there is a bias or there is no bias for the 5-star ratings among Vine Reviews.
