# Mushroom Classifier
This notebook utlizes the UCI Machine Learning repository dataset on mushrooms. The goal of the project is to examine the mushroom dataset and build a classifier to predict if a mushroom's physical attribute (labeled as categories) determines whether it is edible or poisonous. 
- Dataset source: https://archive.ics.uci.edu/ml/datasets/mushroom

Exploratory data analysis includes plotting each feature by class using matplotlib and a heat map of all features using a Theil's U correlation test. Missing data is imputed for the feature stalk root and veil type was dropped from the dataset for containing only a single category. 

The Random Forest Classifier is the first model used for its ability to work with categorical datasets and handle missing values. It is compared to a Decisions Tree classifier and Gaussian Naive Bayes model. N-estimators and feature importance is calculated. Top predictive features are plotted in charts.
