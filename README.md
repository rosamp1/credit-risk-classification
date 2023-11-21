# credit-risk-classification

# Credit Risk Analysis Report

## Overview

The purpose of this analysis is to evaluate the performance of two Logistic Regression models: one trained on the original data and another trained on resampled data using RandomOverSampler. The goal is to assess the models' accuracy, precision, and recall scores for credit risk assessment.

## Results

### Logistic Regression Model with Original Data

- **Balanced Accuracy Score:** 0.952
- **Confusion Matrix:**

   
- **Classification Report:**


### Logistic Regression Model with Resampled Training Data (RandomOverSampler)

- **Accuracy Score:** 0.994
- **Confusion Matrix:**



- - **Classification Report:**
 
- 
## Summary

Both models demonstrate high accuracy and precision, indicating strong predictive performance. The resampled model, utilizing RandomOverSampler, showcases slightly better results, especially in terms of recall for class 1.

### Recommendation

Considering the high performance of both models, the choice between them may depend on specific business requirements. If emphasis is placed on overall accuracy, either model is suitable. However, if identifying true positives (class 1) is critical, the resampled model is recommended due to its improved recall score for this class.



## Logistic Regression Model Details






