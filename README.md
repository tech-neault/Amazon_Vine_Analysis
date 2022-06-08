# Amazon Vine Analysis

# Overview
The Amazon Vine program is a service that allows sellers, publishers, and manufacturers to get reviews on their products in exchange for compensation. However, there is concern that some of these reviews may be biased as they are in exchange for free product. In this analysis, we selected DVDs from a list of more than 50 item-specific data sets. First we set up our data pipeline, using Google Colab, then using AWS and SQL created a database, then performed further analysis, again in Google Colab.

# Results
### Total reviews - Vine and Non-Vine
##### Vine (paid) - 49
![filtered_paid](https://github.com/tech-neault/Amazon_Vine_Analysis/blob/main/Resources/filtered_paid.png)

##### Non-Vine (unpaid) - 151,400
![filtered_unpaid](https://github.com/tech-neault/Amazon_Vine_Analysis/blob/main/Resources/filtered_unpaid.png)

### 5 Star reviews - Vine, Non-Vine, Overall
##### Vine (paid) - 9
![paid_5star](https://github.com/tech-neault/Amazon_Vine_Analysis/blob/main/Resources/paid_5star.png)

##### Non-Vine (unpaid) - 78,061
![unpaid_5star](https://github.com/tech-neault/Amazon_Vine_Analysis/blob/main/Resources/unpaid_5star.png)

##### Overall 5 Star Reviews - 78,080
![total_5star](https://github.com/tech-neault/Amazon_Vine_Analysis/blob/main/Resources/total_5star.png)

### Percentage of 5 Star Reviews - Vine and Non-Vine
##### Vine (paid) - 18.37%
![percent_paid_5star](https://github.com/tech-neault/Amazon_Vine_Analysis/blob/main/Resources/percent_paid_5star.png)

##### Non-Vine (unpaid) - 51.56%
![percent_unpaid_5star](https://github.com/tech-neault/Amazon_Vine_Analysis/blob/main/Resources/percent_unpaid_5star.png)


# Summary 

As there are only 49 Vine reviews out of 151,449 total reviews for DVDs, it is difficult to conclude if there is a bias among Vine reviews. Out of those 49 Vine reviews, only 9 total were 5 star reviews, at just 18% - compared to Non-Vine reviews that had a far more positive 51% of all reviews being 5 stars.

With over 150,000 reviews on DVDs total, it is possibly surprising that there are so few Vine reviews on these items. This may speak to the rise in streaming platform use as opposed to watching a movie using a DVD. We would suggest that a similar analysis be performed on other types of datasets, including newer technologies, to analyse this further. 
