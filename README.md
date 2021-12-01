# Amazon_Vine_Analysis

## Overview of the analysis: 
The purpose of this analysis is to use PySpark to perform the ETL process to extract a dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin using PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results: 

How many Vine reviews and non-Vine reviews were there?

- There were 355 reviews. All of them were non vine reviews.

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- There were 90 5 star non-Vine reviews. None were Vine reviews

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- 25 percent of the reviews were 5 star. There were no Vine reviews.

Summary: This dataset is drawn from gift card customers. Gift card customers wouldnt be likely to subscribe to vine as a susbribtion is required for gift card purchases. This would lend to the notion that the reviews are not biased. 

