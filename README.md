# IBM HR Attrition Analysis and Modelling

Here, I try to analyze and model the dataset provided by IBM which contains a set of factors that aim to decide if an employee will leave or not. And if they leave, what are the main factors / features ?

The notebook contains the following:

1. **Exploratory Data Analysis (EDA)** using statistics and visualization for a set of different types of features including numeric, ordinal and nominal features and give some comments for each about the found insights for such results.
2. **Feature Engineering** using correlation between the features and the target by different correlation tests and pair-wise correlation between the numeric feautres.
3. **Modelling** using machine learning models including logistic regression, SVM, and random forests with hyperparameter search over a grid of hyperparameters using cross validation to find the optimal model for our data that achieves high *recall* scores. Also, SMOTE oversampling was introduce to check its effect on the imbalance between the target classes. In each step, we check the contribution of the *processed* features using either the coeficient associated with each feature for the linear models or the features' importances for random forests.