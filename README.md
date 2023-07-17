# Predicting Diseases from Symptoms Using Machine Learning

The goal of this project is to solve health-related issues by supporting doctors to more accurately predict and diagnose diseases using machine learning techniques, based on symptoms that patients may be experiencing, making timely treatment a possibility which benefits patient care. 

Using the proposed Disease Prediction dataset that contains 132 parameters, we will conduct a series of modeling on those predictor variables to determine the class variable, prognosis. This project will explore the important features selected and apply them to test against several machine learning algorithms to compare their performance. 
The project will emphasize on the technique of Classification and Regression, Data Mining and Knowledge Discovery. Classification model will be used to predict the type of disease (as a dependent column) from the type of symptoms (as independent columns). 

For predictive modeling, the proposed algorithms used are (1) Logistic Regression, (2) Random Forest, (3) Naïve Bayes, (4) Support Vector Classifier and (5) K-nearest neighbor. These algorithms will be implemented using Python programming language. 

Can the implementation of a supervised machine-learning model be used to determine if diseases can be accurately predicted and diagnosed? 

## Datasource

The data set was retrieved from: 
- (1) https://impact.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html (The New York Presbyterian Hospital provides a database of health symptoms that individuals experienced along with the corresponding prognosis admitted during 2004.) 
- (2) https://github.com/anujdutt9/Disease-Prediction-from-Symptoms 
- (3) https://www.kaggle.com/datasets/neelima98/disease-prediction-using-machine-learning 

##  Project Stages

1.	Abstract 
2.	Introduction
  * Research Questions
3.	Literature Review
4.	Approach
5.	DATA DESCRIPTION
 *  Attributes Summary
6.	DATA PREPROCESSING
  * Handling missing Values
  * Checking Duplicates
  * Outlier Detection
  * Balancing the Dataset
  * Exploring Train Test Split
7.	EXPLORATORY DATA ANALYSIS
  * Initial Analysis
  * Univariate Analysis
  * Bivariate Analysis
8.	CORRELATION
  * Exploring Correlation through Heatmap
  * Matthews Correlation Coefficient
  * Brier Score
9.	FEATURE SELECTION
  * Filter Method
    * Chi Square
    * ANOVA
  * Wrapper Method
    * Forward Selection
    * Backward Elimination
    * Recursive Feature Elimination
  * Embedded Method
    * Decision Tree Based
10.	FEATURE IMPORTANCE
11.	1st iteration model building
12.	CROSS VALIDATION
  * Leave one out
  * Stratified k-fold
  * Holdout method
13.	Hyperparameter tuning
14.	2nd iteration model building
15.	AUC / ROC curve
16.	Conclusion
17.	References
