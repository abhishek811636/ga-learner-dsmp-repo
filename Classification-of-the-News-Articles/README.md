### Project Overview

 We are given references to news pages collected from an web aggregator in the period from 10-March-2014 to 10-August-2014. The resources are grouped into categories that represent pages discussing the same story. News categories included in this dataset include business(b); science and technology(t); entertainment(e); and health


### Learnings from the project

 After completing the project, the goal is to predict  which class a particular resource belongs to given the title of the resource.By  solving it will reinforce the following concepts of text analytics:

Preprocess text data with tokenization, stopword removal etc
Vectorize data using Bag-of-words and TF-IDF approaches
Apply classifiers (Logistic and Multinomial Naive Bayes) to perform multi-class classification


### Approach taken to solve the problem

 To approach the problem, we first preprocessed the data and split into train and test data sets, following on  we vectorized with tf-idf approach,

Futher predicting the values with  Multinomial Naive Bayes and Logistic Regression


