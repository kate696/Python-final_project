# Python-final_project

The aim of this project is to predict whether an individual’s income will be greater than $50,000 per year or not based on census data.
This data was extracted by Barry Becker from the 1994 Census database. (Sourse:<https://archive.ics.uci.edu/ml/datasets/Census+Income>)

## Description of the method to be used

In this project I will use random forest algorithm, this is a natural extension of a decision tree. It uses bagging and feature randomness when building each individual tree to try to create an uncorrelated forest of trees, that allows to buid each tree on the different set of observations.

For this project I will use sklearn.ensemble RandomForestClassifier that is available in Python.

The list of Python packages necessary to run this code is listed in the "requirements.txt" file.
