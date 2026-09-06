# Investigating Gradient Descent for Linear Regression

## Overview

This project investigates how the learning rate affects the convergence of gradient descent when training a simple linear regression model.

The model and gradient descent algorithm were implemented from scratch using NumPy.

## Objective

The main objective is to compare different learning rates and analyze their effect on the speed and stability of convergence.

## Methods

* Simple linear regression
* Mean Squared Error (MSE)
* Gradient descent implemented from scratch
* NumPy for numerical computation
* Matplotlib for visualization
* Learning rates: 0.001, 0.01, and 0.1

## Results

The experiments showed that:

* **0.001:** Converged slowly.
* **0.01:** Converged quickly and stably for this dataset.
* **0.1:** Became unstable and resulted in numerical overflow.

The results demonstrate that choosing an appropriate learning rate is important for successful gradient descent optimization.

## Tools

* Python
* NumPy
* Matplotlib
* Google Colab

## Files

* `gradient-descent-linear-regression.ipynb` — Complete project notebook containing the implementation, experiments, visualizations, and analysis.
