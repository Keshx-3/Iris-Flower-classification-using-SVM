# Iris Flower Classification using Support Vector Machine (SVM)

This repository contains a Support Vector Machine (SVM) model using Python and Sklearn, using the popular Iris dataset.

## Dataset
The Iris dataset is used in this tutorial, which contains 150 samples of iris flowers with four features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The target variable consists of three classes:
- Setosa
- Versicolor
- Virginica

## Project Overview
1. **Data Loading and Exploration**
   - Load the Iris dataset using `sklearn.datasets`.
   - Create a Pandas DataFrame for easier data manipulation.
   - Explore the dataset by viewing sample rows and features.

2. **Data Visualization**
   - Visualize the data by plotting Sepal Length vs. Sepal Width and Petal Length vs. Petal Width.
   - Use Matplotlib for creating scatter plots to differentiate between classes.

3. **Model Training**
   - Split the data into training and testing sets using `train_test_split`.
   - Train the SVM model using the training data.

4. **Model Evaluation**
   - Evaluate the model's performance using the testing data.
   - Experiment with different parameters like Regularization (C), Gamma, and Kernel to tune the model.

## Installation
To run this tutorial, ensure you have Python and the necessary libraries installed:

```bash
pip install numpy pandas scikit-learn matplotlib
