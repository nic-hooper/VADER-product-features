# VADER-product-features
Utilizing VADER sentiment-analysis to analyze product features of clustered Amazon reviews

## Description
This project presents a comprehensive analysis of Amazon user reviews for a specific product category using sentiment analysis methods as well as clustering. The overall goal was to gain insight into the relationship between user reviews and quantified sentiment for the purpose of extracting insights to better inform business decisions.  
The methods used to perform this analysis were the VADER lexicon-based sentiment analysis approach to assign sentiment scores for each user review, next HDBSCAN was used to create clusters based on similar reviews. Finally, the clusters were analyzed based on their average sentiment scores and specific product features were identified which received positive or negative feedback.

## Dependencies
* Data source: https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/
  * (the reviews and metadata datasets from the "Home and Kitchen" category were used)
* Python libraries used:
  * pymongo
  * pandas
  * seaborn
  * vaderSentiment
  * gensim
  * hdbscan
  * sklearn
  * pickle
* Additional requirements:
  * MongoDB
