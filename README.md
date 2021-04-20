# Data-Science-Capstone-Udacity
Final project for the data science nanodegree

## Summary
This capstone project entails an analysis on four different data sets provided by Arvato financial solutions. The first part is an unsupervised analysis on a German demographics data set and a mail-order company's customer data set. The goal here is to implement customer segmentation and determine which individuals are likely to become customers of the mail-order company. The second part is a supervised learning analysis on a data set of targeted individuals by the company to predict whether an individual has bcome a customer. 

## Packages Used
- Seaborn
- Numpy
- Sklearn
- Pandas
- Matplotlib
- Imblearn
- xgboost

## Unsupervised Learning Methods
- StandardScaler
- Principal Component Analysis
- K-Means Clustering

## Supervised Learning Methods
- ADASYN oversampling
- Logistic Regression
- AdaBoost Classifier
- XGBoost Classifier

## Files
- Jupyter notebook of analysis
- CSV files containing cluster centroid descriptions

## Summary of Results
- The target customers tend to be retirees with moderate online affinity who have little or no recent transaction activity.
- The non-target customers are slightly younger people who have higher transaction activity and higher online affinity.
- Out of the three supervised learning models, the logistic regression gave a higher score than the other two models.
