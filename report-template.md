# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis

The purpose of this analysis was to build a model that can identify the creditworthiness of borrowers based on  a dataset of historical lending activity from a peer-to-peer lending services company. The goal of the model is to predict and label healthy-loans as '0' while high-risk loans as '1'.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of the machine learning model.

* Accuracy: the overall correctness of the model is 99%, suggesting that the ratio of correctly predicted observations to the total number of observations is really high for this model. 
* Precision: in the positive class (class 1), the model is correct approximately 85% of the time when it predicts a positive outcome. 
* Recall: the ability of the model to capture all the positive instances is really good as well, approximately 91% of the actual positive instances in the dataset were identified. 

## Summary

Summarise the results of the machine learning models, and include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. For example:

The model demonstrates an impressive overall accuracy of approximately 99%, signifying its ability to correctly predict the class for nearly 99% of instances—a notably high achievement. Adding to this accomplishment, the model's F1-score, which gauges the balance between precision and recall, is also around 99%, emphasizing the exceptional equilibrium in its predictive performance.

Moreover, when we delve into the specifics, the F1-score for class 0, representing healthy loans, reaches an outstanding 100%, underscoring the model's precision and recall harmony for this class. However, for class 1, corresponding to high-risk loans, the F1-score slightly decreases to 85%.

This discrepancy in F1-scores is attributed to the inherent imbalance within our original dataset. The substantial disparity in the number of instances labeled as '0' or healthy loans (75036 instances) compared to those labeled '1' or high-risk loans (2500 instances) has likely introduced a bias towards healthy-loan instances in our model. Given the context, prioritizing the accurate prediction of high-risk loans becomes pivotal. To address this, I recommend collecting more high-risk loan data and subsequently retraining our model with this expanded dataset. This iterative approach aims to enhance the model's predictive power, especially in identifying high-risk loans.

