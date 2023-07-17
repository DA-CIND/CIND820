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

1.	[ABSTRACT](https://github.com/DA-CIND/CIND820/blob/main/Abstract%20-%20Revised.pdf) 
2.	INTRODUCTION
  * Research Questions
     - Can we accurately predict disease using machine learning? 
     - Which correlation technique will be used in a binary dataset?
     - Which feature selection technique will be appropriate for this dataset?
     - Which machine learning algorithms are most effective in producing reliable results? 
     - What method of cross validation evaluation will be employed?
     - Can the ML algorithms' settings be tuned for the optimal performance? 

3. [LITERATURE REVIEW](https://github.com/DA-CIND/CIND820/blob/main/Literature%20Review.pdf)
4.	[APPROACH](https://github.com/DA-CIND/CIND820/blob/main/Approach.pdf)
5.	[DATA DESCRIPTION](https://github.com/DA-CIND/CIND820/blob/main/Data%20Description.pdf)
 *  Attributes Summary
6.	[DATA PREPROCESSING](https://github.com/DA-CIND/CIND820/blob/main/Data%20Preprocessing.ipynb)
  * Handling missing Values
  * [Checking Duplicates](https://github.com/DA-CIND/CIND820/blob/main/Duplicate%20Check.ipynb)
  * Outlier Detection
  * Balancing the Dataset
  * Exploring Train Test Split
7. [EXPLORATORY DATA ANALYSIS](https://github.com/DA-CIND/CIND820/blob/main/EDA(EXPLORATORY%20DATA%20ANALYSIS)-Final.ipynb)
  * Initial Analysis
  * Univariate Analysis
  * Bivariate Analysis
8.	[CORRELATION](https://github.com/DA-CIND/CIND820/blob/main/Exploring%20Correlation.ipynb)
  * Exploring Correlation through Heatmap
  * Matthews Correlation Coefficient
  * Brier Score
9.	[FEATURE SELECTION](https://github.com/DA-CIND/CIND820/blob/main/Feature%20Selection-Final.ipynb)
  * Filter Method
    * Chi Square
    * ANOVA
  * Wrapper Method
    * Forward Selection
    * Backward Elimination
    * Recursive Feature Elimination
  * Embedded Method
    * Decision Tree Based
10.	[FEATURE IMPORTANCE](https://github.com/DA-CIND/CIND820/blob/main/Feature%20Importance-Final.ipynb)

The code for the below is all combined into [one](https://github.com/DA-CIND/CIND820/blob/main/1st%2C2nd%20iteration%2CCross%20Validation%2C%20Hypertuning.ipynb) file

11.	1st ITERATION MODEL BUILDING
12.	CROSS VALIDATION
  * Leave one out
  * Stratified k-fold
  * Holdout method
13.	HYPERPARAMETER TUNING
14.	2nd ITERATION MODEL BUILDING
15.	AUC / ROC curve
16.	Conclusion
17.	References
