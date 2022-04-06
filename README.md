# yelp_customers_experience_optimization

Nowadays, both consumers and merchants are relying on review sites such as Yelp when genuine feedback for business is needed. This project aims to predict customers’ ratings by analyzing their reviews about the restaurant on different platforms, detect fake reviews in comments, and analyze key factors that influence customers’ preference on restaurants. 

The problem is addressed through a combination of Yelp company reviews dataset, merchant information dataset, filtered fake review dataset, etc. These datasets are used to perform multiple machine learning algorithms and the success of these models will be compared using performance metrics such as F-1 score, AUC, etc.    

Goals: 
1. Predict rating [like, dislike] , [star1 ~ star5] for reviews written on other social media. 
2. Identify FAKE reviews. 
3. Analyze key factors that influence customers' preference on restaurants. 

Methods: 
Binary classification; Multiclass classification; Aspect Based Sentiment Analysis


Platforms: Google Cloud Platform, PySpark: Spark NLP, John Snow Lab


Models: 
Binary classification:  Logistic Regression, Random Forest, Linear SVC 
Aspect Based Sentiment Analysis: Named-entity recognition


Challenges: 
1. Imbalanced Data: fake reviews with labels
   Solution: Undersampling, Oversampling, Class weight 
2. Platform Limitation: PySpark does not have a  SMOTE package 








