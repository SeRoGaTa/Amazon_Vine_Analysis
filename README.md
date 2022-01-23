# Amazon Vine Analysis

***Version 1.0.0***

---

## Overview of Project
#### This project is about a dataset provide by Amazon Reviews. Each datasets presented is from a specific product and we were ask to pick one product to perform an ETL process in which we extract the data, transform it with different groupby's, filters and more and then load them to AWS instance. By other hand, we were also requested to analyze the dataset for any bias regarding the reviews from Vine members vs. no members. This comparison was analyzed only in the 5 stars received on the review dataset

Regarding the files you'll find here, let me explain them:

* Amazon_Reviews_ETL.ipynb - This file contains the code to extract, transform and load the dataset from Amazon reviews and load it up to AWS instance.
* Vine_Review_Analysis.ipynb - This file contains the code from the extract and transform the dataset in order to get the specific data to analyze the bias of reviews
* Resources - Here you'll find the pictures I took from my code to complement my ReadME

## Results
#### 

- How many Vine reviews and non-Vine reviews were there?
  - Here we have 94 reviews for the Vine members and 40471 revies from the non-Vine members. 
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - We have 41 reviews for the Vine community and 12508 in the non-Vive members with 5 stars
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - As a percentage 43.6% for the Vine members and 30.9% for the non-Vine members
 
<img src="https://github.com/SeRoGaTa/Amazon_Vine_Analysis/blob/main/Resources/result_delivery2_paid.png" width="700">
<img src="https://github.com/SeRoGaTa/Amazon_Vine_Analysis/blob/main/Resources/result_delivery2_unpaid.png" width="700">

## Summary
#### As a results, after all the transformation needed, I found we do have a trend on the Vine members vs. No Vine members, as you can see in the bullets above, we have a bigger percentage of 5 stars from the Vine community vs the no Vine members, with this said, we can say there is a positive trend to 5 stars in the Vine community. 

As a disclosure I'd also want to add that the two sets of data (Vine vs Non-Vine) has a big difference in quantity since the Vine members reviews is just the .2% (94) of the complete population (40565) so with this small sample it's hard to have a trend but at the end these is the data obtained and the results are gotten from there.

I think we might add another analysis where we split the data in months and get the same test out of each month and then summarize them to see a graph that could confirm the bias in favorable reviews.

Please find the complete analysis of vines here [Amazon Vine Analysis](https://github.com/SeRoGaTa/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb) and the resources presented out of this folder [Resources](https://github.com/SeRoGaTa/Amazon_Vine_Analysis/tree/main/Resources)
