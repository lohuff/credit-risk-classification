# Credit Risk Analysis Report

## Overview
 In this challenge, we were tasked to train and evaluate a model based on loan risks. The model used a dataset of historic lending activity from a peer-to-peer lending services company, including whether the loan was “healthy" or "high-risk”. The model trained on 75% of the data in order to learn trends and then make predictions against the remaining 25% of the data. The accuracy of the predictions versus the test data is how we were able to determine the model’s overall performance. The model was then used again on resampled data in order to further see how well it performed. Based on the model’s performance, we can use it to identify the creditworthiness of borrowers in the future and determine the nature of their loans (healthy vs. high-risk). 
 
 ## Results
 
### Original Data:
- Accuracy score: 0.99
- Precision score (Healthy Loans): 1.00
- Precision score (High-risk Loans): 0.85
- Recall score (Healthy Loans): 0.99
- Recall score (High-risk Loans): 0.91

### Resampled Data:
- Accuracy score: 0.99
- Precision score (Healthy Loans): 1.00
- Precision score (High-risk Loans): 0.84
- Recall score (Healthy Loans): 0.99
- Recall score (High-risk Loans): 0.99


## Summary
Based on the outcome, the model performed very well. It was almost perfect (0.99) in accuracy for both the original data and the resampled data. It was also very precise in predicting the healthy loans in both data sets. However, using the resampled data, the model performed slightly worse in precision for high-risk loans, but 8% better in recall. In summation, I would recommend this model to help determine loan safety, as its results show it performs very well. 
