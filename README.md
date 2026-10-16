# Simple Linear Regression from Scratch

This repository contains a custom Python implementation of a Simple Linear Regression (SLR) model built from scratch. The custom model is benchmarked against Scikit-Learn's `LinearRegression` class to validate its mathematical accuracy and computational efficiency.

## Overview

Instead of relying on iterative `for` loops, this implementation utilizes vectorized NumPy operations to calculate the slope (m) and y-intercept (c) efficiently. 

The notebook covers:
1. Data loading and preprocessing.
2. Building the custom `SLR` class using NumPy.
3. Training both the custom model and the Scikit-Learn model.
4. Comparing parameters and error metrics.

## Files
* `Simple_Linear_Regression_from_scratch.ipynb`: The main Jupyter Notebook containing the code and comparative analysis.
* `placement (1).csv`: The dataset used for training and testing.

## Dataset

The models are trained to predict a student's salary package based on their academic performance:
* **Feature (X):** `cgpa` (Cumulative Grade Point Average)
* **Target (y):** `package` (Salary package)

The data is split into an 80% training set and a 20% testing set (random state 42).

## Results & Validation

The custom NumPy implementation perfectly matches Scikit-Learn's optimized model in both parameter calculation and predictive accuracy.

**Parameter Comparison:**
* **Custom SLR:** Slope (m) = 0.5743 | Intercept (c) = -1.0270
* **Scikit-Learn:** Slope (m) = 0.5743 | Intercept (c) = -1.0270

**Performance Metrics (Mean Absolute Error):**
* **Custom SLR MAE:** 0.231
* **Scikit-Learn MAE:** 0.2315

## Requirements
To run the notebook locally, ensure you have the following dependencies installed:
* `pandas`
* `numpy`
* `scikit-learn`
* `jupyter`

## Usage

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)# Simple Linear Regression from Scratch

This repository contains a custom Python implementation of a Simple Linear Regression (SLR) model built from scratch. The custom model is benchmarked against Scikit-Learn's `LinearRegression` class to validate its mathematical accuracy and computational efficiency.

## Overview

Instead of relying on iterative `for` loops, this implementation utilizes vectorized NumPy operations to calculate the slope (m) and y-intercept (c) efficiently. 

The notebook covers:
1. Data loading and preprocessing.
2. Building the custom `SLR` class using NumPy.
3. Training both the custom model and the Scikit-Learn model.
4. Comparing parameters and error metrics.

## Files
* `Simple_Linear_Regression_from_scratch.ipynb`: The main Jupyter Notebook containing the code and comparative analysis.
* `placement (1).csv`: The dataset used for training and testing.

## Dataset

The models are trained to predict a student's salary package based on their academic performance:
* **Feature (X):** `cgpa` (Cumulative Grade Point Average)
* **Target (y):** `package` (Salary package)

The data is split into an 80% training set and a 20% testing set (random state 42).

## Results & Validation

The custom NumPy implementation perfectly matches Scikit-Learn's optimized model in both parameter calculation and predictive accuracy[cite: 5].

**Parameter Comparison:**
* **Custom SLR:** Slope (m) = 0.5743 | Intercept (c) = -1.0270
* **Scikit-Learn:** Slope (m) = 0.5743 | Intercept (c) = -1.0270
  
**Performance Metrics (Mean Absolute Error):**
* **Custom SLR MAE:** 0.2315
* **Scikit-Learn MAE:** 0.2315

## Requirements

To run the notebook locally, ensure you have the following dependencies installed:
* `pandas`
* `numpy`
* `scikit-learn`
* `jupyter`

## Usage

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
