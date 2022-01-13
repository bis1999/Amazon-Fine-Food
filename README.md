# Amazon-Fine-Food
The data was taken from https://www.kaggle.com/snap/amazon-fine-food-reviews
## Introdcution
This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

In this project, I analyzed textual data which consists of amazon product reviews. The end goal here is was to classify the reviews into positive or negative. Further, I used various vectorization techniques such as Bag of Words and TD-IDF. I used Logistic regression to classify the reviews. TF-IDF Logistic Regression performed the best test achieving a roc-AUC score of 0.968. 
