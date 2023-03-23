# Module 12 Report Template

## Overview of the Analysis

The purpose of the analysis is to train a model that can classify and identify the creditworthiness of borrowers The dataset is of historical lending activity and what I am trying to predict are the people who are likely to default on a loan. To compare the performance, I build two models and used LogisticRegression method on one, and RandomOverSampler on the other.

## Results

* Machine Learning Model 1 (LogisticRegression method):
  - __Precision__: 0.87, out of all the loans that the model predicted would be a high-risk loan, only 87% actually was. 
  - __Recall__: 0.89, out of all the loans that acutally were high risk, the model predicted this outcome correctly for 89% of them.
  - __The F1 Score__:for healhy loan is 1 and for high risk loan is 0.88, which means this model does a better job predicting whehter a loan is healthy than it does with high-risk loans. 



* Machine Learning Model 2 (RandomOverSampler method):
  - __Precision__: 0.99, out of all the loans that the model predicted would be a high-risk loan, only 99% actually was. 
  - __Recall__: 0.99, out of all the loans that acutally were high risk, the model predicted this outcome correctly for 99% of them.
  - __The F1 Score__:0.99 for both heathy loans, which means this model does a better job predicting both heathy and high-risk loans.

## Summary
Overall the ML Model 2 has a better performance when it comes to identify the creditworthiness of borrowers. Becuase it is more important to predict the high-risk loans and the elimitae the risk, and the ML Model 2 has 0.99 F1 score on it as well as the overall perforamnce. 