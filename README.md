# Amazon_Vine_Analysis
## Purpose
The purpose of this analysis was to look at Amazon customer review data for a product category of our choice, to see if being paid through the Amazon Vine Program had a meaningful impact on the review written.  I personally chose health and beauty, because it is where I most often see amazon products being pushed by influencers and reviewers.  I personally thought that being paid to review a beauty product would have a positive impact on reviews 


## Overview 
I extracted the Health and Beauty dataset into a datafrane,then transformed that into four separate dataframes that match the table schema created within pgAdmin.  I will reupload once I can get my pgAdmin to work and and load those new dataframes there.

I continued with PySaprk in Google CoLab notebooks to determine if there was any bias towards reviews that we written as part of the Vine program, we were tasked with  determining if having a paid review made a difference in the percentage of five-star reviews.

## Results 
### Paid Reviews 
Of the total reviews, 497 of them were paid (only .4% of the total reviews).  
Of the paid reviews, 220 or 44% were 5 star reviews.  
### Unpaid Reviews 
Of the total reviews, 120863 of them were unpaid.
Of the unpaid reviews, 74470 or 61% were 5 star reviews.  
### Overall 
This result actually surprised me, overall being a paid review had a negative impact on whether or not it was 5 stars.  Something else I thought was interesting what how few reviews in the health and beauty category were of vine participants.  I think comparing the numbers of paid viewers accross subjects would be an interesting place to continue this research.  

