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




