# logistic-regression-with-regularization-and-polynomial-features-to-predict-whether-a-student-gets-admitted-into-a-university

## Description

This project aims to demonstrate the implementation of logistic regression with polynomial features. The code provided performs binary classification on a dataset using a logistic regression model with polynomial terms. It visualizes the decision boundary and calculates the training accuracy.

## Motivation

The motivation behind this project is to understand and apply logistic regression with polynomial features for non-linear classification problems. By extending logistic regression to include polynomial terms, I can capture complex relationships between features and improve the model's ability to separate classes.

## Problem Solving

The project solves the problem of classifying data points into two classes based on their features. It uses logistic regression with polynomial features to learn a decision boundary that separates the classes. The model predicts the class labels and evaluates the training accuracy. The provided code also includes a function to plot the data points and decision boundary for visualization.

## Key Learnings

Through this project, I gain the following insights:

- Implementing logistic regression with polynomial features
- Using regularization (ridge) to control overfitting
- Visualizing the decision boundary and training data
- Evaluating the model's performance using accuracy

## Usage

The code provided can be executed in MATLAB or Octave. Simply run the script, and it will load the dataset, preprocess the features, train a logistic regression model, and visualize the results.

### Required Libraries/Dependencies

- MATLAB R2018a or later

### Instructions

1. Ensure MATLAB is installed on your system.
2. Open MATLAB and navigate to the project directory.
3. Load the provided dataset using `X = load('data2.txt')`.
4. Extract the class labels and remove the third column from the dataset.
5. Create the polynomial feature matrix up to power 6.
6. Set the regularization parameter (`lambda`) and train the logistic regression model using `fitclinear`.
7. Compute the training accuracy of the model.
8. Plot the data points and decision boundary using the `plotMdlData` function.
9. Customize the plot labels and legend if needed.
10. Run the script and observe the results.


## Acknowledgements

The project utilizes the following libraries:

- MATLAB Statistics and Machine Learning Toolbox

## License

This project is licensed under the [MIT License](LICENSE).
