# Amazon Vine Analysis
## Overview
The purpose of this analysis was to analyze Amazon reviews written by members of the paid Amazon vine program for video games. The data was to be used to see if there was a bias between paid reviews, and unpaid reviews.

## Results
To make sure the results were acurate, and usable, the data was filtered in the following ways:

* The data was filtered for reviews with greater than or equal to 20 votes
* The data was filtered for reviews with greater than or equal to 50% helpful votes
* The data was then separated into two data sets
  * Paid reviews
  * Unpaid reviews
* Three pieces of data were then determined for each of the final two data sets (Paid and UnPaid):

How many reviews?

![Screen Shot 2022-07-05 at 8 15 49 PM](https://user-images.githubusercontent.com/93801125/177444711-e7230271-f866-4939-86b6-5c176a982c96.png)
![Screen Shot 2022-07-05 at 8 15 59 PM](https://user-images.githubusercontent.com/93801125/177444734-2659cb6b-84ef-4fba-b858-9b7cb007990d.png)


How many reviews were 5 stars?

![Screen Shot 2022-07-05 at 8 16 14 PM](https://user-images.githubusercontent.com/93801125/177444756-23274f56-4477-4ca8-b5d1-cf8f8c256389.png)
![Screen Shot 2022-07-05 at 8 16 33 PM](https://user-images.githubusercontent.com/93801125/177444782-dd392a36-146e-413a-bd43-fb2c610e901c.png)


What percentage of reviews were 5 stars?

![Screen Shot 2022-07-05 at 8 16 42 PM](https://user-images.githubusercontent.com/93801125/177444814-a91f75e6-4591-4a3f-83cc-53543d4028a4.png)
![Screen Shot 2022-07-05 at 8 16 50 PM](https://user-images.githubusercontent.com/93801125/177444836-74eac060-0094-4085-a748-7ec4d947b9e0.png)

## Summary
Based upon the analysis results shown above, there is indeed a bias in the Amazon vine program towards 5-star reviews as a result of being paid.

However, because of the huge difference of review sizes (the sample size of paid reviews was only 90 reviews vs the sample size of unpaid reviews of 37831), it wouldn't be wise to base any meaningful conclusions to this data.

An additional analysis is recommended.  Because the 5 star rating is very limiting and finite, it may be helpful to expand the range to 4 star ratings and above, splitting it up into 4 star, 4.5, and 5 star buckets and see if the bias continues in these other ratings.
