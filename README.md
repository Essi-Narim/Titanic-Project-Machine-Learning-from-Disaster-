# Titanic Project: Machine Learning from Disaster!

The aim of this notebook is to provide a step-by-step walkthrough of how a data scientist tackles a problem. Specifically, we'll be looking at the challenge of predicting whether an individual survived the infamous Titanic shipwreck.

## Overview

1. **Shape Analysis**: understanding the data shape through methods like histograms and box plots.
2. **EDA (Exploratory Data Analysis)**: exploring the data to identify any patterns or insights that may be useful for modeling.
3. **Data Cleaning**: cleaning the data to ensure it's consistent and free from errors or inconsistencies.
4. **Feature Engineering & Data Pre-Processing for ML**: creating new features that may help improve model accuracy.
5. **Machine Learning**
   - Model Building (Baseline Validation Performance)
   - Model Tuning (hyperparameter tuning)
   - Ensemble Learning
   - Predictions
6. **Deep Learning**
   - TensorFlow {Multi-Layer Perceptron (MLP) classifier}
   - SKLEARN {Multi-Layer Perceptron (MLP) classifier}

## Machine Learning

### Model Building (Baseline Validation Performance)

We'll start by building baseline models for each algorithm, assessing their performance without any tuning or optimization. This will give us an idea of which algorithms perform better out-of-the-box and provide a baseline for comparison once we've tuned the models.

### Model Tuning (Hyperparameter Tuning)

We'll then proceed to tune each model's hyperparameters to optimize their performance. This will involve methods such as GridSearchCV and manual tuning to find the best combination of hyperparameters for each algorithm.

### Ensemble Learning

Once we have optimized each model, we'll explore ensemble learning methods to potentially further improve the performance of our models. This may include techniques such as bagging, boosting, and stacking.

### Predictions

Finally, we'll use the best-performing models to make predictions on the test data and evaluate their performance using various metrics.

## Deep Learning

### TensorFlow {Multi-Layer Perceptron (MLP) classifier}

We'll use TensorFlow to build a Multi-Layer Perceptron (MLP) classifier, a type of neural network. We'll start by defining the architecture of the network, including the number of layers, the number of neurons in each layer, and the activation functions. We'll then train the model on the pre-processed data and evaluate its performance.

### SKLEARN {Multi-Layer Perceptron (MLP) classifier}

We'll also build an MLP classifier using SKLEARN. This will involve defining the architecture of the network, as well as any hyperparameters such as the learning rate, maximum number of iterations, and solver algorithm. We'll then train the model and evaluate its performance.

## Conclusion
This project provides a comprehensive walkthrough of the data science, machine learning, and deep learning processes. By following these steps and experimenting with various techniques, we aim to create accurate and robust models for predicting the survival of individuals on the Titanic.
