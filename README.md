# ML-Decision-Tree-and-Random-Forest-master
a project of machine learning course to write from scratch decision tree algorithm and random forest algorithm of classification, multi-classification, regression.


Data:
1)	Train: rows 1-19,034. 
2)	Validation: rows 19,035-24,130.
3)	Test: rows 24,131-end.
4)	The Excel file containing two sheets:
a.	adult_income_data- working data.
b.	feature_desc- feature description and possible values.
5)	Data Source: http://archive.ics.uci.edu/ml/datasets/Adult (I already removed NA values for you).

Section A (Coding) :
1)	Implement a decision tree algorithm in Python.
2)	Implement a random forest algorithm in Python.

Section B (Implementation): 
1)	Classification: Use both models from section A and predict whether adult income with a given feature (all feature) has an income which is bigger than 50K$ in year, or not.
2)	Regression:  Use both model from section A and predict adult education years with the following features: age, workclass, fnlwgt, martial-status, relationship, race, sex, capital-gain, capital-loss, hours-per-week, native-country. 
3)	Multiclassification: Use both model from section A and predict adult education status with the following features: age, workclass, fnlwgt, martial-status, relationship, race, sex, capital-gain, capital-loss, hours-per-week, native-country.

Scores:
1) Classification:
a. Decision Tree: 0.86188 Accuracy
b. Random Forest: 0.8516 Accuracy
2) Multiclassification: 
a. Decision Tree: 0.3626 Accuracy
b. Random Forest: 0.3616 Accuracy
3) Regression:
a. Decision Tree: 5.5845 MSE
b. Random Forest: 5.61107 MSE
