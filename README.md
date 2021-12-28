# Boston-House-Price-Prediction

# Regularization--


![lasso and ridge](https://user-images.githubusercontent.com/81983943/145536202-bd5dbf99-c686-4437-9fe9-f92647668d4e.jpg)

One of the major aspects of training your machine learning model is avoiding overfitting. The model will have a low accuracy if it is overfitting. This happens because your model is trying too hard to capture the noise in your training dataset. By noise we mean the data points that don’t really represent the true properties of your data, but random chance. Learning such data points, makes your model more flexible, at the risk of overfitting.

This is a form of regression, that constrains/ regularizes or shrinks the coefficient estimates towards zero. In other words, this technique discourages learning a more complex or flexible model, so as to avoid the risk of overfitting.

# 1-L1(Lasso Regression)-->

![lasso](https://user-images.githubusercontent.com/81983943/145536395-3a22db78-cfa7-4d91-8cf4-1bef3e2c014c.png)

# 2-L2(Ridge Regression)-->

![ridge](https://user-images.githubusercontent.com/81983943/145536482-a1b9a260-105e-4705-aea2-385ed54bcd6e.png)

# other methods of increase accuracy of dataset--

1- Corss Validation --> Cross-validation is a resampling procedure used to evaluate machine learning models on a limited data sample. The procedure has a single parameter called k that refers to the number of groups that a given data sample is to be split into. As such, the procedure is often called k-fold cross-validation

![cross val](https://user-images.githubusercontent.com/81983943/145537318-eadbc4be-1e07-48df-9d79-b99d78f56307.png)

2- Pipeline Model--> Used models like polynomial features, standard scalar, linear regression, lasso, ridge etc to make pipeline and processed the dataset to find better accuracy.
