# Amazon Vine Analysis

[Link to ETL Code](https://github.com/c-geisel/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_ETL.ipynb)

[Link to Review Analysis Code](https://github.com/c-geisel/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb)

## Overview of the analysis 
Companies can pay a fee to establishments (such as Amazon Vine) to write reviews for their products. In this project, 50 datasets are supplied and analysis on one is performed. The ETL process is used to connect to an AWS RDS instance and then load the transformed data into pgAdmin. After this, Pandas is used to determine if there is any bias toward favorable reviews from the reviews written that were paid for. 

## Results 
PUT IN IMAGES 

After transforming and uploading the dataset, an analysis is performed. The total reviews are found, the number of paid and unpaid reviews are found, and the percentage of paid and unpaid reviews that were five star are found. The following results were found: 
- Overall, there was a total of 51,123 paid (vine) and unpaid (non-Vine) reviews of all star ratings.. 
- 257 vine reviews were 5 star
- 25,216 non-Vine reviews were 5 star
- 42.34% of Vine reviews were 5 star.
- 49.92% of non-Vine reviews were 5 star.

## Summary
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
