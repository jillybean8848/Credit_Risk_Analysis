# Credit_Risk_Analysis
## Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, multiple techniques were necessary in order to train and evaluate this model. These techniques were ran and evaluated for performance and accuracy at predicting credit risk.

The machine learning methods used to evaluate credit risk were:
 * RandomOverSampler
 * SMOTE
 * ClusterCentroids
 * SMOTEENN
 * BalancedRandomForestClassifier
 * EasyEnsembleClassifier

## Results:

### Naive Random Oversampling
 * Accuracy Score: 64.6%
 * Accuracy Score: 67.4%
 * Precision High Risk: 1%
 * Precision Low Risk: 100%
 * Recall High Risk: 71%
 * Recall Low Risk: 58%

![naive_random_oversampling](https://user-images.githubusercontent.com/110632671/206835034-4fd04bf5-520c-4398-92f0-28cefc96dd87.png)

### SMOTE Oversampling
 * Accuracy Score: 65.8%
 * Precision High Risk: 1%
 * Precision Low Risk: 100%
 * Recall High Risk: 63%
 * Recall Low Risk: 68%

![SMOTE](https://user-images.githubusercontent.com/110632671/206835136-c996afef-a787-491d-8225-6df195e0b677.png)

### Cluster Centroid Undersampling
  * Accuracy Score: 65.8%
  * Precision High Risk: 1%
  * Precision Low Risk: 100%
  * Recall High Risk: 69%
  * Recall Low Risk: 40%

![cluster_centroid_undersampling](https://user-images.githubusercontent.com/110632671/206835271-33192843-400d-46d2-811c-746699ca9256.png)

### SMOTEEN
  * Accuracy Score: 54.4%
  * Precision High Risk: 1%
  * Precision Low Risk: 100%
  * Recall High Risk: 72%
  * Recall Low Risk: 57%
 
![SMOTEENN](https://user-images.githubusercontent.com/110632671/206835379-ea7c3210-8b6a-41fa-baa7-1be4787b38f3.png)

### Balanced Random Forest Classifier
 * Accuracy Score: 78.7%
 * Precision High Risk: 4%
 * Precision Low Risk: 100%
 * Recall High Risk: 67%
 * Recall Low Risk: 91%

![bfc](https://user-images.githubusercontent.com/110632671/206835645-ef8e7882-439c-4100-873e-ff2fd3bc1df0.png)

### Easy Ensemble Classifier
 * Accuracy Score: 92.5%
 * Precision High Risk: 7%
 * Precision Low Risk: 100%
 * Recall High Risk: 91%
 * Recall Low Risk: 94%

![easy_ensemble](https://user-images.githubusercontent.com/110632671/206835757-a82e6733-6141-4567-9aa6-af0834ff2d8f.png)

## Summary 
As I previously stated, credit-risk is very difficult to predict. While the Easy Ensemble AdaBoost Classifier performed with the highest accuracy at 92.5% all other models left substantial room for error. All models performed poorly when it came to determening high credit risk. It is my opinion that machine learning would not be the best model to use when determining credit risk. 
