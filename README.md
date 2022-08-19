# Amazon_Vine_Analysis

## Purpose of the analysis of the Vine program:
-Pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance.

-Load the transformed data into pgAdmin. 

-Use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results:
1. How Vine reviews and non-Vine reviews were there?

Total Vine reviews: 613

Total non-Vine reviews: 64968

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Total Vine reviews 5 stars: 222

Total non-Vine reviews 5 stars: 30543

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

% of Vine reviews 5 stars: 36%

% of non-Vine reviews 5 stars: 47%

## Summary:
From the results, Vine members did not show bias when rating their products. Their 5 star rating is about 10% less than Non-Vine members (36% vs. 47%). We can say that Vine members are less biased and more objective when submitting a review. 

To support a bias, more data is needed from different productsto support this assumption further, we should include all of the data rather than filtering it to a percentage of helpful vs. total votes as we did for this analysis. Reviewing the data as is would give us more information and allow us to further support our assumption as shown below.
