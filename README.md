# Naive-Bayes-Algorithm
This repository contains implementation of Naïve Bayes Algorithm used to solve a binary classification problem.

The program takes two inputs: a training dataset and a test dataset which is extracted from "breast-cancer.csv" file. All the features in this dataset are categorical and the last column of the dataset is the class variable. I have renamed the the two class values as: positive and negative.

The program first loads the training dataset, calculates all required probabilities, and then predicts the class of each instance in the test set. As a result, the program adds a new column containing the predicted classes to the test set and saves it as "predictions.csv" file and shows accuracy, sensitivity and specificity on the console.

