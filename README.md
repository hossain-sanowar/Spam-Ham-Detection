# Spam-ham-Detection

# Project Overview:

This project's major purpose is to give a thorough analysis of some of the most prominent machine learning algorithms for SMS spam filtering1. Two sorts of data must be analysed: spam data and ham data. The data is divided into training and test sets so that the model can be trained using the train set and its performance can be evaluated using the test set.

In this research, five machine learning techniques, including Naive Bayes, RandomForestClassifier, KNeighborsClassifier, Support Vector Machines, DecisionTreeClassifier, LogisticRegression, are used to perform email spam filtering. Then, performance metrics such as the accuracy, precision, and confusion matrix are produced for each model. GridSearchCV is then used to fine-tune these models by evaluating all possible combinations of hyper parameters and selecting the model with the highest score.

# Model Building
The Model-Building Process

1. Setting up features and target as X and y
2. Splitting the testing and training sets
3. Build a pipeline of model for four different classifiers.
  - Naïve Bayes
  - RandomForestClassifier
  - KNeighborsClassifier
  - Support Vector Machines
  - DecisionTreeClassifier
  - LogisticRegression

`Ham or spam?` SMS messages are identified using a machine learning technique. There are other current ways for spam filtering, however the focus of this project is limited to the usage of the stated machine learning algorithms. All models such as Naive Bayes, RandomForestClassifier, KNeighborsClassifier, Support Vector Machines, DecisionTreeClassifier, LogisticRegression have been applied and their performance metrics have been determined. The parameters are hyper-tuned using GridSearchCV to determine which parameters have the highest score. The Suport vector machine model is picked for this project since it has the highest score compared to the other models. The performance measures are recalculated after re-feeding this model with the optimal parameters discovered during fine tuning.
