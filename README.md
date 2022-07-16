# Spam-Email-Detection

Ham or spam? SMS messages are identified using a machine learning technique. There are other current ways for spam filtering, however the focus of this project is limited to the usage of the stated machine learning algorithms. All models such as Naïve Bayes, RandomForestClassifier, KNeighborsClassifier, Support Vector Machines, DecisionTreeClassifier, LogisticRegressionhave been applied and their performance metrics have been determined. The parameters are hyper-tuned using GridSearchCV to determine which parameters have the highest score. The Suport vector machine model is picked for this project since it has the highest score compared to the other models. The performance measures are recalculated after re-feeding this model with the optimal parameters discovered during fine tuning.

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
