# classification

This repository is dedicated to classification problems.

1st we use amazon reviews to classify sentiment of users in a baby-products range. 
The classification is logistic regression problem as it is either positive or negative. As of now, I have not considered decision boundary
cases but will do that next when I learn to do so.
We see how we can implement Logistic regression where we predict and also find probablity that a given input will have positve or negative 
sentiment. Also we see how we can use gradient ascent algorithm for learning logistic regression classifier. Given coefficients, how we can
predict sentiments. 
We check the accuracy of either ways.
We generate wordclouds. Also we generate most positve reviews and vice-versa, which gives an insight into which products are doing well.
From positive words and vice versa, we can get insight into where we are doing right / wrong in terms of product quality, shipment, 
manufacturing etc.

The second american'96 is about an inbuilt dataset of american elections in 1996, which shows implementation of adaboost classifier to 
predict to whom will the vote go. It compares default decision tree model of adaboost with svc and we find that decision tree does way 
better with 90% accuracy compared to svc.
