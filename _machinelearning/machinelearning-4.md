---
title: "Feature Selection for Wine Classification"
excerpt: "Built several classification models for predicting wine classes using a subset of features obtained by applying various methods of feature selection.<br/>"

collection: machinelearning
---
<br/>
[GitHub](https://github.com/ciDSproj/wine_classification)

---


The models built in this project for wine classification used a subset of the original features as good predictors of the target. For selecting the features, I applied filter and wrapper methods and L1 and L2 regularization techniques as penalties against model complexity.


Below are some plots showing the top features selected by different techniques.



<img src='/images/ml3_corr_feature.png'>



<img src='/images/ml3_sequential_feature.png'>



Here we can see the relative importance of the features in the wine dataset using a random forest model.



<img src='/images/ml3_feature_import.png'>
