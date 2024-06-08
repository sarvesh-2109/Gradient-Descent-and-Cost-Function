# Gradient Descent and Cost Function

This repository contains an implementation of gradient descent for linear regression, along with a comparison to scikit-learn's linear regression implementation.

## Overview

The main goal of this project is to demonstrate how to implement gradient descent for linear regression and compare the results with scikit-learn's linear regression model. The gradient descent algorithm is used to find the best-fit line for a set of data points by iteratively adjusting the slope and intercept to minimize the cost function.

## Dataset

The dataset used for this project is `test_scores.csv`, which contains the following columns:
- `math`: Scores in mathematics.
- `cs`: Scores in computer science.

## Files

- `Gradient_Descent_and_Cost_Function.ipynb`: Jupyter Notebook containing the implementation and explanation.
- `test_scores.csv`: Dataset file used for training the model.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/sarvesh-2109/Gradient-Descent-and-Cost-Function.git
cd Gradient-Descent-and-Cost-Function
```

2. Install the required libraries:

```bash
pip install numpy pandas scikit-learn
```

## Usage

1. Open the Jupyter Notebook:

```bash
jupyter notebook Gradient_Descent_and_Cost_Function.ipynb
```

2. Run the cells in the notebook to see the implementation and results.

## Code Explanation

### Libraries

- `numpy`: For numerical operations.
- `pandas`: For data manipulation.
- `scikit-learn`: For comparison with the built-in linear regression model.

### Gradient Descent Implementation

The `gradient_descent` function implements the gradient descent algorithm to find the best-fit line. The function iteratively adjusts the slope (`m_curr`) and intercept (`b_curr`) to minimize the cost function.

### Scikit-learn Comparison

The `predict_using_sklean` function uses scikit-learn's `LinearRegression` class to fit the model and returns the slope and intercept for comparison with the gradient descent implementation.

## Results

The results from the gradient descent implementation are compared with those from scikit-learn to verify the accuracy of the implementation.

### Example Output

```python
Using gradient descent function: Coef 1.0177367382394566 Intercept 1.9150804342724986
Using sklearn: Coef [1.01773624] Intercept [1.91521931]
```

## Conclusion

This project demonstrates the implementation of gradient descent for linear regression and validates the results by comparing them with scikit-learn's linear regression model. The close match between the two sets of results indicates the correctness of the gradient descent implementation.

