---
date: 2022-11-09T10:58:08-04:00
description: "A model that predicts whether a client will subscribe to a term deposit."
featured_image: "/images/proj01.png"
title: "Predicting Bank Telemarketing Success"
---
* In the banking industry, a lot of importance is given to telemarketing as high profits are obtained with reduced costs. An intelligent decision support system(DSS) is required to efficiently help in the prediction of the client's subscription to the deposits. This project attempts to create a tool to support the client selection decision based on telemarketing campaigns conducted by the banking industry. The classification goal of this model is to predict if the client will subscribe to a term deposit or not.
* Created a classification model using a machine learning pipeline to predict whether a client will subscribe to a term deposit to assist the bank in identifying potential clients who are most likely to subscribe to a term deposit. 
* Created a machine learning pipeline that used several classification algorithms including XGBoost, Random Forest, Support Vector Classifier, and Logistic Regression with L1 and L2 regularization. 
* After evaluating these models, I selected the best one with an F-beta score of 0.9. Finally, I used SHAP to interpret the model's predictions.

Sample visualization of Exploratory Data Analysis:
{{< figure src="/images/proj1-2.png" >}}
{{< figure src="/images/proj1-4.png" >}}
{{< figure src="/images/proj1-5.png" >}}

Visualization of Model Interpretation:

Global Feature Importance:
{{< figure src="/images/proj1-1.png" >}}
Local Feature Importance:
{{< figure src="/images/proj1-3.png" >}}


[Link to GitHub Repository](https://github.com/Sagarika-Ramesh/Predicting_bank_telemarketing_success)
