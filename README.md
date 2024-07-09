# Iris Species Classification

This project demonstrates various machine learning algorithms applied to the Iris dataset for classification purposes. The project includes data preprocessing, model training, and evaluation using multiple algorithms such as Linear Regression, Logistic Regression, Decision Tree, Random Forest, Naive Bayes, and K-Nearest Neighbors.

## Project Structure

- `iris_classification.ipynb`: Jupyter notebook containing the entire workflow from data loading to model evaluation.
- `README.md`: Documentation for the project.

## Dataset

The Iris dataset is a famous dataset that contains the following information:

- Features: Sepal length, Sepal width, Petal length, Petal width
- Target: Species of iris flowers (Setosa, Versicolor, and Virginica)

## Preprocessing

The preprocessing steps include:

1. Loading the dataset using `sklearn.datasets`.
2. Converting the dataset into a pandas DataFrame for easier manipulation and analysis.
3. Splitting the data into training and testing sets using `train_test_split`.

## Models

### Linear Regression

Linear Regression is used to predict the continuous target values. However, since the target in the Iris dataset is categorical, Linear Regression is not the best fit. It's included here for demonstration purposes.

### Logistic Regression

Logistic Regression is used for binary classification, but it can be extended to multiclass classification problems.

### Decision Tree

Decision Tree is a simple and intuitive model used for both classification and regression tasks.

### Random Forest

Random Forest is an ensemble learning method that constructs multiple decision trees during training and outputs the mode of the classes for classification tasks.

### Naive Bayes

Naive Bayes is a probabilistic classifier based on Bayes' theorem with strong independence assumptions between features.

### K-Nearest Neighbors

K-Nearest Neighbors (KNN) is a simple, instance-based learning algorithm used for both classification and regression.

## Dependencies

- pandas
- numpy
- matplotlib
- scikit-learn

## Results

The accuracy of each model is printed.

## Conclusion

This project demonstrates the application of various machine learning algorithms to the Iris dataset. It covers the complete workflow from data preprocessing to model evaluation, providing a comprehensive understanding of each step involved in a machine learning project.
