# Iris-ml-classification-model-for-Beginners-
Machine learning model used to predict the species of the iris flower

# Iris ML Classification Model
This repository contains a machine learning project that performs classification on the Iris dataset using Support Vector Machine (SVM) and Decision Tree classifiers.

## Overview
The Iris dataset is a classic dataset in the field of machine learning and statistics. It consists of 150 samples of iris flowers from three different species: Iris-setosa, Iris-versicolor, and Iris-virginica. Each sample has four features: sepal length, sepal width, petal length, and petal width.

## Dataset
The Iris dataset is included in the `sklearn` library, so no external download is required. The dataset can be loaded directly using `sklearn.datasets.load_iris`.
### Features
- **Sepal Length**: The length of the sepal in centimeters.
- **Sepal Width**: The width of the sepal in centimeters.
- **Petal Length**: The length of the petal in centimeters.
- **Petal Width**: The width of the petal in centimeters.
- **Species**: The species of the iris flower (target variable).


## Machine Learning Algorithms Used
### Support Vector Machine (SVM)
Support Vector Machine (SVM) is a supervised machine learning algorithm that can be used for both classification or regression challenges. It performs classification by finding the hyperplane that best divides a dataset into classes.
#### Key Points:
- Suitable for linear and non-linear data.
- Effective in high-dimensional spaces.
- Uses different kernel functions like linear, polynomial, RBF (Gaussian), and sigmoid to transform the data.

### Decision Tree Classifier
A Decision Tree is a non-parametric supervised learning method used for classification and regression. It splits the data into subsets based on the value of input features, leading to a tree with decision nodes and leaf nodes.
#### Key Points:
- Simple to understand and interpret.
- Capable of handling both numerical and categorical data.
- Prone to overfitting if not pruned properly.

## Results
- The SVM and Decision Tree classifiers are compared based on their accuracy and confusion matrices.
- Insights on model performance and potential improvements are discussed.

## Conclusion
This project demonstrates the use of SVM and Decision Tree classifiers on the Iris dataset. Both models are effective in classifying the iris species, with SVM generally providing better accuracy due to its ability to handle high-dimensional data and various kernel functions.
