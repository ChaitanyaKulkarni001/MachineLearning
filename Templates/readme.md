
# Supervised Learning

Supervised learning is a type of machine learning where a model is trained on a labeled dataset. Each training example consists of an input (features) and the corresponding output (label). The goal is to learn a mapping from inputs to outputs so that the model can predict labels for unseen data.

## Types of Supervised Learning

### 1. Regression

Regression is used to predict continuous values. The output variable is a real-valued number, and the model attempts to capture the relationship between the features and the target variable.

#### Common Regression Algorithms

- **Linear Regression**: 
  - Models the relationship between the independent variable (features) and the dependent variable (target) using a linear equation.
  
- **Multiple Linear Regression**: 
  - Extends linear regression by using multiple features to predict the target.

- **Polynomial Regression**: 
  - A form of regression where the relationship between the independent variable and the dependent variable is modeled as an \( n^{th} \) degree polynomial.

- **Decision Tree Regression**: 
  - Uses a tree-like model to make predictions by splitting the data into subsets based on feature values.

- **Random Forest Regression**: 
  - An ensemble method that builds multiple decision trees and averages their predictions for more robust results.

### 2. Classification

Classification is used to predict categorical values. The output variable is a class label, and the model assigns an input to one of the predefined categories.

#### Common Classification Algorithms

- **Logistic Regression**: 
  - A statistical method for predicting binary classes using a logistic function to model the probability of class membership.

- **K-Nearest Neighbors (KNN)**: 
  - A non-parametric method that classifies new instances based on the majority class of their nearest neighbors in the feature space.

- **Decision Tree Classification**: 
  - Similar to regression but used for classifying data by splitting it into branches based on feature values until reaching a leaf node representing a class label.

- **Random Forest Classification**: 
  - An ensemble method that builds multiple decision trees for classification and combines their results to improve accuracy and reduce overfitting.

- **Support Vector Machine (SVM)**: 
  - A powerful classification technique that finds the hyperplane that best separates classes in the feature space. **Kernel SVM** uses kernel functions to handle non-linearly separable data.

- **Naive Bayes**: 
  - A probabilistic classifier based on Bayes' theorem, assuming that the presence of a feature is independent of the presence of any other feature given the class label.

## Summary Table

| Algorithm              | Type                | Description                                                   |
|-----------------------|---------------------|---------------------------------------------------------------|
| Linear Regression      | Regression           | Predicts continuous values using a linear equation.          |
| Multiple Linear Regression | Regression       | Extends linear regression to multiple features.               |
| Polynomial Regression  | Regression           | Models relationships as a polynomial function.                |
| Decision Tree Regression| Regression          | Uses tree structure to predict continuous values.             |
| Random Forest Regression| Regression          | Ensemble of decision trees for robust predictions.            |
| Logistic Regression     | Classification      | Predicts binary classes using a logistic function.            |
| K-Nearest Neighbors (KNN)| Classification     | Classifies based on majority class of nearest neighbors.      |
| Decision Tree Classification| Classification  | Uses tree structure to classify data.                         |
| Random Forest Classification| Classification  | Ensemble of decision trees for classification tasks.          |
| Support Vector Machine (SVM)| Classification  | Finds the hyperplane that best separates classes.             |
| Naive Bayes            | Classification      | Probabilistic classifier based on feature independence.       |

