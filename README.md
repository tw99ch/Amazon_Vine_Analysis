# Amazon_Vine_Analysis
## Overview of the analysis:
The purpose of this analysis is to evaluate if there is any bias on the Amazon products review from Vine members using the AWS RDS database with tables in pgAdmin and PySpark.

## Results:
- How many Vine reviews and non-Vine reviews were there
There were 47 vine reviews and 8362 non-vine reviews.

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There were 15 5-stars reviews from vine and 4332 non-vine reviews from non-vine.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
The percentage of 5-stars vine reviews were 31.91% and 51.81% 

## Summary: 
From the summary above, there is no positivity bias for reviews in the Vine program. There were only 47 vine reviews and 15 of them gave 5 stars reviews of 31.91%. Whereas, there were 8362 non vine reviews, 4332 of them gave 5 stars reviews of 51.81%. Non vine reviews gave more 5 stars reviews them vine reviews. The result may not be conclusive that the vine reviews has positivity bias for reviews. This may be due to there is no enough vine reviews for watch catogory product, as it might me more expensive with less vine reviews.

The additional analysis that I could do with the dataset is that we can get the price for the reviewed product then see if there is any bias for the vine reviews as vine reviews may have bias over expensive products then the cheap one.
