# Amazon_Vine_Analysis
## Overview 
The purpose of this project is to determine if there is any bias toward favorable reviews from Vine members in the selected dataset using PySpark.
## Results
Two dataframes(paid_reviews and unpaid_reviews) were created using PySpark where the original dataset was filtered where the percentage of helpful_votes was equal to or greater than 50%.
The total number of reviews, the number of 5-star reviews, and the percentage of 5-star reviews were calculated for all Vine(Paid) and non-Vine(Unpaid) reviews.
### Analysis of Vine reviews
- Total number of Vine reviews are 1448.
- Out of that, the total number of 5 star reviews are 647.
- Percentage of 5-star Vine reviews is 44.68%
### Analysis of non-Vine reviews
- Total number of Vine reviews are 90768.
- Out of that, the total number of 5 star reviews are 44104.
- Percentage of 5-star Vine reviews is 48.59%
## Summary
The percentage of the Vine mmbers 5-star reviews is 44.68% whereas non-Vine members contributed to 48.59% of the 5-star reviews. Based on the above numbers, we can say that isn't any positive bias for reviews in the Vine program. 
To support the above conclusion, we can make the following analysis.
- Total number of negative reviews.
- Percentage of negative reviews for Vine and non-Vine members.
