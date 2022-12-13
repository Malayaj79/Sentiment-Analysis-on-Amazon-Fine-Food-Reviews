# Sentiment-Analysis-on-Amazon-Fine-Food-Reviews
Amazon Fine Food Reviews Analysis Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

Number of reviews: 568,454 Number of users: 256,059 Number of products: 74,258 Timespan: Oct 1999 - Oct 2012 Number of Attributes/Columns in data: 10

## Attribute Information:

Id  
ProductId - unique identifier for the product  
UserId - unqiue identifier for the user  
ProfileName  
HelpfulnessNumerator - number of users who found the review helpful  
HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not  
Score - rating between 1 and 5  
Time - timestamp for the review  
Summary - brief summary of the review  
Text - text of the review  

## Objective: Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2).  

SQLite3  
Text Preprocessing  
Tf-Idf  
Bag of Words  
Logistic Regression  
Naive Bayes  
