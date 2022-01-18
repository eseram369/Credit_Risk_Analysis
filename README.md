# Credit_Risk_Analysis
## Overview of the Analysis

## Purpose
### A hypothetical peer-to-peer lending services company wants to use machine learning to predict credit risk. They help to build and evaluate several ML models, oversampling and undersampling the data and evaluating the models' performance to see how well they predict data. Management believes this will provide a quicker and more reliable loan experience and more accurate identification of suitable candidates for loans.

## Results
## Outputs from All Six Models
- The naive random oversampling algorithm resulted in a balanced accuracy score of 0.64. The precision score was 1.0 for predicting low risk but extremely low for predicting high risk (0.01). The recall scores were 0.66 and 0.62 for high and low risk, respectively.

![1](https://user-images.githubusercontent.com/90746609/149885087-cfcd18af-9c15-4cdf-a961-f45a961e509b.jpg)

- The SMOTE algorithm resulted in a balanced accuracy score of 0.64. The precision for predicting high and low risk was the same as the naive random oversampling algorithm. The recall scores were 0.66 and 0.62 for high and low risk, respectively.

![2](https://user-images.githubusercontent.com/90746609/149885880-0ce4279f-feb5-4f5c-9b9e-4fbd19e86844.jpg)

- The SMOTEENN algorithm resulted in a resulted in a balanced accuracy score of 0.65. The precision for predicting high and low risk was the same as all the previous algorithms. The recall scores were 0.61 and 0.69 for high and low risk, respectively.


![3](https://user-images.githubusercontent.com/90746609/149886372-a658506a-71b5-479c-8e1d-c964ed6416cd.jpg)


- The Balanced Random Forest Classifier resulted in a resulted in a balanced accuracy score of 0.79. The precision score was 1.0 for predicting low risk, but very low for predicting high risk (0.09). The recall scores were 0.92 and 0.94 for high and low risk, respectively.


![4](https://user-images.githubusercontent.com/90746609/149886770-33a2b7b3-4ff6-4bff-bd1c-0632ce0337c9.jpg)


- The Easy Ensemble Classifier resulted in a resulted in a balanced accuracy score of 0.93. The precision and recall scores for predicting high and low risk were the same as the Balanced Random Forest Classifier.

![5](https://user-images.githubusercontent.com/90746609/149886922-25fea426-6441-42bc-9929-26a82163e364.jpg)

## Summary
### Undersampling the data using the Cluster Centroids algorithm yielded the lowest balanced accuracy score of 0.55. The precision scores for predicting high risk were low for all six models. The Balanced Random Forest Classifier and the Easy Ensemble Classifier gave the highest recall scores of 0.92 and 0.94 for high and low risk, respectively. I would recommend using the Easy Ensemble Classsifer because it had the highest balanced accuracy score of 0.93, although the company should be aware of the implications of the precision scores. The precision score of 0.09 means that a high-risk classification is unreliable.


