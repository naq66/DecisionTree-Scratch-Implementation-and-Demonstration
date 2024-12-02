# Decision Tree Classifier Implementation

This repository contains a **custom implementation of a Decision Tree Classifier** in Python. The project is designed to provide an in-depth understanding of decision tree algorithms, including their theoretical foundation, practical implementation, and evaluation on a real-world dataset. It is ideal for those who want to learn how decision trees work from scratch, without relying on prebuilt libraries.

---

## Project Overview

A **Decision Tree** is a tree-structured model used in machine learning for both classification and regression tasks. It divides data into subsets based on feature values, creating a hierarchy of decision nodes, branches, and leaf nodes. Each internal node represents a decision rule, and each leaf node provides a class prediction. This step-by-step approach mimics human logic, making decision trees highly interpretable.

This project demonstrates the step-by-step implementation of a Decision Tree Classifier, focusing on key components such as Gini Impurity, recursive splitting, and handling both numerical and categorical features. The implementation was applied to the **Adult dataset** from the UCI Machine Learning Repository, which contains demographic and income information.

---

## Features

- **Custom Implementation**: The Decision Tree Classifier is built from scratch, without using libraries like scikit-learn, allowing a deeper understanding of its inner workings.
- **Support for Mixed Features**: The classifier supports both numerical and categorical features, making it versatile for various datasets.
- **Visualization**: The project includes a tree plotting function to visualize the decision-making process clearly and intuitively.
- **Hyperparameter Tuning**: The implementation supports tuning of key parameters like `max_depth` and `min_samples_per_leaf` to optimize performance.
- **Evaluation Metrics**: The model is evaluated using accuracy, precision, recall, F1 score, and a classification report to provide a comprehensive performance analysis.

---

## Dataset

The **Adult dataset** was used for demonstration. It contains demographic and income information, with the goal of predicting whether an individual's income exceeds \$50K per year. The dataset was preprocessed to handle missing values, balance class distributions, and select relevant features for building the decision tree.
