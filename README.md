# Amazon_Vine_Analysis

## Overview of the analysis
The purpose of this analysis is to investigate reviews on Video games among Vine members and non-members. Using PySpark, the data set was Extract, Transform, and Loaded to the necessary criteria. The results are summarized below.

## Results of the analysis
The following questions were answered after the ETL process.

1.  **How many Vine reviews and non-Vine reviews were there?**
There are 94 Vine reviews compared to 40,471 non-Vine reviewers. These data were extracted using the following codes.

2. **How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**
Out of the 94 Vine reviews, 48 of them were rated 5 stars. As with the 40,471 non-Vine reviewers, 15,663 of them were rated 5 stars. The following codes were used to get the numbers.

3. **What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?** 
Based on the calculation, about 51.06% of the Vine reviews were 5 stars. As with the non-Vine reviews, only 38.70% of them were 5 stars

## Summary
Based on how high of a percentage the number of 5 stars were for Vine members, there is a positive bais towards the review. More than half of paid Vine members had 5 star ratings versus less than 40% of non-paid Vine members. This clearly shows that paid members have a more positive view of Video Games than those who don't pay. Rather than analyzing data this way, a recommendation can be to do a statistical distribution looking at all star ratings for skewness. 


