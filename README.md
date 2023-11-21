# credit-risk-classification

# Credit Risk Analysis Report

## Overview

The purpose of this analysis is to evaluate the performance of two Logistic Regression models: one trained on the original data and another trained on resampled data using RandomOverSampler. The goal is to assess the models' accuracy, precision, and recall scores for credit risk assessment.

## Results

### Logistic Regression Model with Original Data
- **Classification Report:**
- **Balanced Accuracy Score:** 0.952 This suggests that the model performs well in terms of sensitivity (recall) for both classes, taking into account the class imbalance.
- **Precision Score:** Precision measures the accuracy of the positive predictions made by the model. For class 0 (negative class): 1.00 means that when the model predicts class 0, it is correct 100% of the time. For class 1 (positive class): 0.85 means that when the model predicts class 1, it is correct 85% of the time.
- **Recall Score:** Recall,For class 0: 0.99 means that the model correctly identifies 99% of the actual class 0 instances. For class 1: 0.91 means that the model correctly identifies 91% of the actual class 1 instances.

<img width="273" alt="image" src="https://github.com/rosamp1/credit-risk-classification/assets/132237292/1828e95b-aba0-474c-970e-70f94f62219f">

  
### Logistic Regression Model with Resampled Training Data (RandomOverSampler)
- **Classification Report:**
- **Accuracy Score:** 0.994 indicates that the model accurately predicts the target variable in almost 99.4% of the cases.
- **Precision Score:** For class 0: 1.00 means that when the model predicts class 0, it is correct 100% of the time. For class 1: 0.84 means that when the model predicts class 1, it is correct 84% of the time.
- **Recall Score:** For class 0: 0.99 means that the model correctly identifies 99% of the actual class 0 instances. For class 1: 0.99 means that the model correctly identifies 99% of the actual class 1 instances.
  
<img width="272" alt="image" src="https://github.com/rosamp1/credit-risk-classification/assets/132237292/31ad4f0d-dee8-49ae-bb32-b1539b681f16">
 
## Summary

Both models demonstrate high accuracy and precision, indicating strong predictive performance. The resampled model, utilizing RandomOverSampler, showcases slightly better results, especially in terms of recall for class 1.

### Recommendation

Considering the high performance of both models, the choice between them may depend on specific business requirements. If emphasis is placed on overall accuracy, either model is suitable. However, if identifying true positives (class 1) is critical, the resampled model is recommended due to its improved recall score for this class.










