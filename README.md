# Logistic-Regression-Vs-Support-Vector-Machine-Comparison
When should we use Support Vector Machines Versus Logistic Regression for Classification? I compare both when there are a different number of predictors (p) and a different percentage of Trained (m) and Tested (1000-m) data. 

The Data: The data used is German Credit information. Many different metrics are used to decide whether an individual should be accepted for a credit card. Both classification methods aim at sorting the data into a binary accept for a credit card or reject.

I produce a table where p =5,10,20 (P is Columns selected or Predictors used) and
m =600,700,800 (m is rows of data trained) m Training, 1000-m Validation

I used Pandas, Numpy, Matplotlib, and sklearn for the majority of my work. 

What is Support Vector Machine?
A support vector machine (SVM) is machine learning algorithm that analyzes data for classification and regression analysis. SVM is a supervised learning method that looks at data and sorts it into one of two categories. An SVM outputs a map of the sorted data with the margins between the two as far apart as possible. It uses the mathematical concept of Euclidean space. The farther the space in between both categories, the better. This helps us better classify data. 

What is Logistic Regression?
Logistic regression is one of the most popular Machine Learning algorithms, which comes under the Supervised Learning technique. It is used for predicting the categorical dependent variable using a given set of independent variables. Logistic regression predicts the output of a categorical dependent variable. Unlike SVM, Logit regression separates based on if the predictors move the number closer to the desired classification. Numbers are not 1 or 0, they are usually something like .7. If below .5, it becomes 0. If above .5 the number is treated as 1. 

