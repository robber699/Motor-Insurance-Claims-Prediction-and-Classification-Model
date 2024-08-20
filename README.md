# Motor Insurance Claims Prediction and Classification Model

## Overview
This repository contains code and documentation for developing a predictive model for motor insurance claims. Using the dataset `A2 DatasetXX.csv`, the goal is to estimate the frequency of claims and classify high-risk policies based on various modeling techniques. The dataset includes features such as car weight, annual distance driven, driver age, car age, and driver gender, with the claims count following a Poisson distribution.

## Tasks
1. **Linear Model Estimation**
   - Estimate the Poisson rate parameter λ(x) using linear, quadratic, and interaction terms.
   - Report and benchmark the model with specific feature values and visualize the results.

2. **Poisson Regression Tree**
   - Fit a Poisson regression tree and determine the optimal tree size.
   - Plot the final tree and benchmark the estimates against the linear model.

3. **Poisson Boosting Tree (No Base Model)**
   - Apply Poisson boosting tree with no initial base model.
   - Determine the number of boosting steps, tree size, and shrinkage parameter.
   - Benchmark and visualize the estimates.

4. **Poisson Boosting Tree (With Base Model)**
   - Use the base model from the linear regression task for Poisson boosting.
   - Assess the optimal parameters and visualize results.

5. **Neural Network Model**
   - Implement a one-layer neural network with 10 neurons using TensorFlow/Keras.
   - Estimate λ(x) using integer covariates and visualize results.

6. **Model Comparison**
   - Compare all models using 10-fold cross-validation to select the best model.

7. **Logistic Regression Classification**
   - Introduce a categorical variable `High` based on claims count.
   - Develop a logistic regression classifier to predict `High` and visualize probabilities.

## Getting Started
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/motor-insurance-claims.git
   cd motor-insurance-claims
