# Amazon_Vine_Analysis
## Overview 
The purpose of this project is to determine if there is any bias toward favorable reviews from Vine members using PySpark.
## Results
Two dataframes (paid_reviews_df and unpaid_reviews_df) were created using PySpark where the original dataset was filtered for percentage of helpful_votes equal to or greater than 50%.
The total number of reviews, the number of 5-star reviews, and the percentage of 5-star reviews were calculated for all Vine (paid) and non-Vine (unpaid) reviews.
### Analysis of Vine reviews
The following analysis was observed for the Vine reviews.
- Total number of Vine reviews are 1448.
- Out of that, the total number of 5 star reviews are 647.
- Percentage of 5-star Vine reviews is 44.68%

![paid_reviews](https://github.com/chinzjay/Amazon_Vine_Analysis/blob/main/paid_reviews.PNG)
|:--:|
|Fig 1. Code snippet for Vine reviews|

### Analysis of non-Vine reviews
The following analysis was observed for the non-Vine reviews.
- Total number of Vine reviews are 90768.
- Out of that, the total number of 5 star reviews are 44104.
- Percentage of 5-star Vine reviews is 48.59%

![unpaid_reviews](https://github.com/chinzjay/Amazon_Vine_Analysis/blob/main/unpaid_reviews.PNG)
|:--:|
|Fig 2. Code snippet for non-Vine reviews|

## Summary
The percentage of 5-star reviews for Vine members is 44.68% whereas non-Vine members contributed to 48.59% of the 5-star reviews. Based on the above numbers, we can say that there isn't any positive bias for reviews in the Vine program. 
To further support the conclusion, we can make the following analysis.
- Total number of negative reviews.
- Percentage of negative reviews for Vine and non-Vine members.
