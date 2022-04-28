# Credit Risk Analysis

## Overview
In this project we were looking to predict credit risk by using different machine learning methods to try to predict if the loan is low or high risk credit. We used the following techniques to Resolve Class Inbalance:
- ### Oversampling
  In this section we are going to use the following two algorithms to determine wich one has a best performance:
  - Naive Random
  - SMOTE

- ### Undersampling
  - Cluster Centroides

- ###  Combination Sampling
  In this section we will combine oversampling and undersampling 
  - SMOTEEN

- ### Ensemble Learners
  - Balance Random Forest Classifier
  - Easy Ensemble AdaBoost Classifier

## Results 
-  ### Naive Random Oversampling
  - Balanced accurancy 65%
  - High risk precision is 1% and sensitivity (recall) of 61%
  - Low risk precision is 100% and 68% of sensitivity (recall)
  - Overall there is a 99% precision and 68% sensitivity (reall)

<img width="1103" alt="Screen Shot 2022-04-28 at 7 19 24 AM" src="https://user-images.githubusercontent.com/95391094/165742868-78b81752-577b-4af8-9b0e-08b4c7799d9d.png">

- ### SMOTE Oversampling
  - Balanced accurancy 62%
  - High risk precision is 1% and sensitivity (recall) of 61%
  - Low risk precision is 100% and 64% of sensitivity (recall)
  - Overall there is a 99% precision and 64% sensitivity (reall)

<img width="947" alt="Screen Shot 2022-04-28 at 7 33 42 AM" src="https://user-images.githubusercontent.com/95391094/165743478-1e80e99b-13c6-4496-8945-0f2f722cf59b.png">

- ### Cluster Centroids
  - Balanced accurancy 51%
  - High risk precision is 1% and sensitivity (recall) of 60%
  - Low risk precision is 100% and 43% of sensitivity (recall)
  - Overall there is a 99% precision and 43% sensitivity (reall)

<img width="906" alt="Screen Shot 2022-04-28 at 7 38 07 AM" src="https://user-images.githubusercontent.com/95391094/165744039-1fd46245-57b4-4c60-9b14-612f356feae0.png">

- ### Combination (Over and Under) Sampling
  - Balanced accurancy 65%
  - High risk precision is 1% and sensitivity (recall) of 69%
  - Low risk precision is 100% and 62% of sensitivity (recall)
  - Overall there is a 99% precision and 62% sensitivity (reall)

<img width="923" alt="Screen Shot 2022-04-28 at 7 42 21 AM" src="https://user-images.githubusercontent.com/95391094/165744678-b03ac1b2-287a-4c5a-805c-c3b608634d78.png">

- ### Balanced Random Forest Classifier
  - Balanced accurancy 81%
  - High risk precision is 3% and sensitivity (recall) of 71%
  - Low risk precision is 100% and 90% of sensitivity (recall)
  - Overall there is a 99% precision and 90% sensitivity (reall)

<img width="913" alt="Screen Shot 2022-04-28 at 7 45 23 AM" src="https://user-images.githubusercontent.com/95391094/165745118-53ccb0c2-24fa-497f-b5b4-c31823db4e7c.png">

- ### Easy Ensemble AdaBoost Classifier
  - Balanced accurancy 92%
  - High risk precision is 7% and sensitivity (recall) of 91%
  - Low risk precision is 100% and 94% of sensitivity (recall)
  - Overall there is a 99% precision and 94% sensitivity (reall)

<img width="960" alt="Screen Shot 2022-04-28 at 7 48 29 AM" src="https://user-images.githubusercontent.com/95391094/165745643-6bb6bd3b-fe65-45b9-a359-d590ff811996.png">

## Summary
The results show that the balanced accurancy for the oversampling, undersampling and the combination is not as high as the ensemble models were we can see how it significantly increasses in this models. Precision is really low in high risk status wich might cause many false positives. But as in balance accurancy, the ensemble models are a bit more presice than the others. After this, we can infer that the model with the best performance is the Easy Ensemble model since it has the higher balanced accurancy, presicion and recall values.

