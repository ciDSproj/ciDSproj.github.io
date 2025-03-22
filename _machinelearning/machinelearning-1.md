---
title: "Loan Classification"
excerpt: "The goal of this project was to build a classifier to predict whether a loan will be paid back, based on a dataset containing information on the loan structure and the borrower. After a thorough data analysis, I built several classification models.<br/>"

collection: machinelearning
---
<br/>
[GitHub](https://github.com/ciDSproj/loan_classification)


---

Data exploration highlighted the relationships between numerical variables across distinct categories in loan purpose. Using visualizations, I could observe if loans with the same purpose have similar qualities not shared by loans with differing purposes.


In training and evaluating the classification models, I accounted for the class imbalance in the target variable  that has fewer examples of loans not fully paid. 



<img src='/images/ml1_cm.png'>



<img src='/images/ml1_cm_resample.png'>



I also considered the importance of accurately predicting whether a loan will not be paid back rather than if a loan is paid, as failing to detect loan defaulters can lead to significant financial losses for the institution. The precision-recall curve allows us to visualize these metrics at various threshold levels and observe the tradeoff between the two.