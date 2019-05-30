# Classification-Initial-Scores
A python notebook used to automate the process of looking for the best initial classification machine learning model.

This notebook will consist of a main function diagnose(), which takes **X**: a numeric values only DataFrame which has features, and **y**: a numeric values only DataFrame which has labels, and returns a DataFrame showing scores of trained models *sorted descendingly*.

This diagnosis will consist of these models:
* K Nearest Neighbour
* Logestic Regression
* Gaussian Naive Bays Classifier
* Decision Trees
* Boosted Trees
* Random Forest
* Support Vector Machine (rbf, linear, poly)
