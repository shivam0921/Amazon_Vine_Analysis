# Amazon_Vine_Analysis #


## Overview of the Analysis ##
Using Google Colab notebook, pyspark, and sample reviews from an Amazon S3 database the purpose of this project was to determine  specifically on the five star reviews, and this analysis is focusing on the reviews of the US Grocery. 


## Tools Used

- [x] Amazon Web Services(including RDS and S3)
- [x] Postgres, pgAdmin
- [x] Google Colaboratory
- [x] PySpark, Python. 

## Results ##

The results can be reviewed in the ipynp file located [link to results](https://github.com/shivam0921/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb) 

* **How many Vine reviews and non-Vine reviews were there?** 

A total of 28,287 unpaid reviews for Us Grocery were in the sample set and 61 paid Vines Review were in the sample.

* **How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?** 

A total of 15,689 unpaid 5 star reviews were in the sample database and only 20 paid  5 star reviews were in the data.

* **What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**  
 
 The percentage of Vine 5 star reviews that were paid was 0.12% of total reviews (both paid and unpaid). This is significantly less than the unpaid 5 stars reviews which equated to 99.87% of total unpaid reviews. 


## Summary ##
Given the significantly larger percentage of 5-star reviews in the unpaid population vs. the paid population it is clear that the paid Vine reviews, and 5-star reviews in particular, would not have a significant impact on the overall bias. What is not clear, however, is if that small percentage of paid  5 star reviews had an impact on those who submitted positive unpaid reviews. An additional analysis that could explore whether the paid reviews had an influence over the positively of the unpaid reviews is to look at the date and time when the paid 5-star reviews were posted vs. the unpaid positive reviews.
