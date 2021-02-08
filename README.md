# Amazon_Vine_Analysis

## Overview

The purpose of this analysis was to further our understanding of the extract, transform, load process in a big data environment. We accomplished this by gaining familiarity with tools such as AWS, PySpark and Google Collaboratory. In this exercise, we saved Amazon review datasets (Musical Instruments in my case) to our Amazon S3 bucket, extracted and transformed the data using PySpark, connected Postgres to our AWS server and loaded the results into Postgres. 

## Results

* Q:How many Vine reviews and non-Vine reviews were there?

A: There were 59 vine (paid) reviews and 13,452 non-vine (unpaid) reviews


* Q:How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

A: 34 vine reviews were 5 stars. 7674 non-vine reviews were 5 stars.

* Q: What percentage of Vine reviews were 5 stars? What percentage of non-vine reviews were 5 stars?

A: About 58% of vine reviews were 5 stars. About 57% of non-vine reviews were 5 stars

## Summary

Q: Is there any positivity bias for reviews in the Vine program?

A: There doesn't appear to be any positivity bias in Vine program as the non-vine reviews had nearly the same percentage of 5 star reviews.

Q: What would be an additional analysis that you could do with the dataset to support your statement.

A: To further determine if there is positivity bias in Vine reviews, we could look at 4 star reviews as well. This would increase the sample size of the population of total reviews we could look at since 4 stars is considered to still be positive.
