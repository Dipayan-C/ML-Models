# Machine Learning Models (From Scratch)

## Overview

This project implements a selection of core machine learning algorithms from first principles using NumPy, without relying on high-level libraries such as scikit-learn or TensorFlow.

The aim is to develop a clear understanding of:

* The mathematical foundations of common models
* How optimisation algorithms are applied in practice
* The behaviour of models across different types of data

The project covers three areas:

* Regression
* Classification
* Neural Networks

---

## Project Scope

The repository includes implementations of:

* Linear Regression using maximum likelihood estimation
* Elastic Net regularisation combining L1 and L2 penalties
* Support Vector Machines (SVM) trained with stochastic gradient descent
* Kernel methods, including radial and sigmoid kernels
* A Multi-Layer Perceptron (MLP) with forward propagation
* Experiments analysing the effect of learning rates on convergence

---

## Datasets

| Dataset  | Task            | Description                                  |
| -------- | --------------- | -------------------------------------------- |
| Abalone  | Regression      | Predicting age from physical measurements    |
| Mushroom | Classification  | Classifying mushrooms as poisonous or edible |
| Fashion  | Neural Networks | Image classification (28×28 pixel inputs)    |

---

## Methods

### Regression

* Closed-form solution for linear regression
* Elastic Net regularisation
* Grid search with cross-validation for hyperparameter selection

### Classification (SVM)

* Linear SVM formulation
* Hinge loss optimisation
* Stochastic Gradient Descent (SGD)
* Kernelised SVM with radial and sigmoid kernels

### Neural Networks

* Multi-layer perceptron (MLP)
* ReLU activation functions
* Glorot (Xavier) initialisation
* Analysis of learning rate impact on training behaviour

---

## Results

* Linear regression showed limited performance on non-linear relationships
* Elastic Net improved generalisation through regularisation
* The SVM achieved strong classification performance on structured data
* Neural network behaviour was sensitive to the choice of learning rate
* Larger learning rates improved convergence speed but could introduce instability

---

## Project Structure

```
ml-models/
│
├── data/          # Datasets used for training and testing
├── notebooks/     # Main Jupyter Notebook implementation
├── src/           # Optional modular Python scripts
├── requirements.txt
└── README.md
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/machine-learning-from-scratch.git
cd machine-learning-from-scratch
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:
   Open:

```
notebooks/MFDS_project.ipynb
```

---

## Technologies Used

* Python
* NumPy
* pandas
* matplotlib

---

## Future Improvements

* Implement full backpropagation for the neural network
* Add standard evaluation metrics (precision, recall, F1-score)
* Compare results with scikit-learn implementations
* Improve modular structure using the `src/` directory

---

## Author

Dipayan Chowdhury

---

## Notes

This project is intended as a learning-focused implementation to demonstrate understanding of core machine learning concepts rather than production-level performance.
