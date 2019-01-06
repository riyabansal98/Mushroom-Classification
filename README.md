# Mushroom-Classification

## Problem Statement:

The problem statement is to classify the class of mushrooms given some features of the mushrooms. 

## Dataset Used:

The given dataset mushrooms.csv contains 8124 training samples with 23 features for each sample. 

## Metrics:

We will use the accuracy score to quantify the performance of our model. The accuracy will tell us what percentage of our test data was classified correctly. The accuracy is a good metric choice because it will be easy to compare our model’s performance to that of the benchmark as it uses the same metric. Using Naive Bayes classifier, we get a accuracy of 99%. 

## Naive Bayes Classifier:


It is a classification technique based on Bayes’ Theorem with an assumption of independence among predictors. In simple terms, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature.
<br>
Naive Bayes model is easy to build and particularly useful for very large data sets. Along with simplicity, Naive Bayes is known to outperform even highly sophisticated classification methods.


![bayes](https://user-images.githubusercontent.com/35702912/50735277-7f6a7b80-11d2-11e9-92ef-63d965a1cb10.png)

## Pros and Cons of Naive Bayes Algorithm:

### Pros:

- It is easy and fast to predict class of test data set. It also perform well in multi class prediction.
- When assumption of independence holds, a Naive Bayes classifier performs better compare to other models like logistic regression and you need less training data.
- It perform well in case of categorical input variables compared to numerical variable(s). For numerical variable, normal distribution is assumed (bell curve, which is a strong assumption).


### Cons:

- If categorical variable has a category (in test data set), which was not observed in training data set, then model will assign a 0 (zero) probability and will be unable to make a prediction. This is often known as “Zero Frequency”. To solve this, we can use the smoothing technique. One of the simplest smoothing techniques is called Laplace estimation.
- On the other side, Naive Bayes is also known as a bad estimator.So the probability outputs are not to be taken too seriously.
- Another limitation of Naive Bayes is the assumption of independent predictors. In real life, it is almost impossible that we get a set of predictors which are completely independent.
