# Machine_Learning_PipeLine


A complete Machine Learning PipeLine
Intoroduction to supervised Machine Learning
What is machine learning?
Types of Machine learning Algorithms
Supervised Machine Learning
Classification vs Regression
Machine Learning Pipeline
Predict the onset of diabetes based on diagnostic measures

Data Preparing

Analyze Data
Descriptive Statitics
Data Visualization
Outliers investigation

Outliers investigation Single Feature
Outliers investigation Pairs
Evaluate Algorithms: Baseline

Feature Engineering

Data Preprocessig
Standard Scaler
MinMax Scaler
Remove OutlierS
Feature Selection

Corrolation
Feature Importance
Ensemble Methods

Algortithm Tuning
Voting Ensemble
Error Corrolation
Stacking
Conclusion (Acuuracy 86%)
add Codeadd Markdown
Intoroduction to supervised Machine Learning:
add Codeadd Markdown
What is machine learning?
Task T: image classification problem of classifying dogs and cats

Experience E: I would give a ML algorithm a bunch of images of dogs and cats

The performance measure P: the ML algorithm could learn how to distinguish a new image as being either a dog or cat.

Machine learning (Machine Learning by Tom Mitchell):

A computer program is said to learn from experience **E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, Improves with experience E.**

add Codeadd Markdown
Types of Machine learning Algorithms
Supervised Learning: Input data is called training data and has a known label or result. Ex: Spam/not-spam or a stock price at a time.

Unsupervised Learning: Input data is not labeled and does not have a known result. EX: Grouping customers by purchasing behavior

Semi-Supervised Learning: Input data is a mixture of labeled and unlabeled examples. EX: a photo archive where only some of the images are labeled, (e.g. dog, cat, person) and the majority are unlabeled.

Reinforcement Learning: a goal-oriented learning based on interaction with environment. Autonomous cars.

add Codeadd Markdown
Supervised Machine Learning
Regression: Linear Regression, Logistic Regression

Instance-based Algorithms: k-Nearest Neighbor (KNN)

Decision Tree Algorithms: CART

Bayesian Algorithms: Naive Bayes

Ensemble Algorithms: eXtreme Gradient Boosting

Deep Learning Algorithms: Convolution Neural Network

add Codeadd Markdown
Classification vs Regression
Classification predicting a label .vs. Regression predicting a quantity.

add Codeadd Markdown
Classification Algorithms Examples:
Linear: Linear Regression, Logistic Regression
Nonlinear: Trees, k-Nearest Neighbors
Ensemble:
Bagging: Random Forest
Boosting: AdaBoost
add Codeadd Markdown
Machine Learning Pipeline:
Define Problem

ML type of problem
Prepare Data

Data Visualization methos ...
Data Selection
Feature Selection methods ..
Feature Engineering methods ..
Data Transormation methods ..
Spot Check Algorithm

Test Harness ...
Perform Measure ...
Evaluate accuracy of different algorithms
Improve Results

Algorithms Turning methids
ensemble methods
Present Results

Save the model
add Codeadd Markdown
Define Problem:
Pima Indians Diabetes Database
Predict the onset of diabetes based on diagnostic measures
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

add Codeadd Markdown
Attribute Information:

Number of times pregnant

Plasma glucose concentration a 2 hours in an oral glucose tolerance test

Diastolic blood pressure (mm Hg)

Triceps skin fold thickness (mm)

2-Hour serum insulin (mu U/ml)

Body mass index (weight in kg/(height in m)^2)

Diabetes pedigree function

Age (years)

Class variable (0 or 1)

