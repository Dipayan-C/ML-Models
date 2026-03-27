# Machine Learning Models from Scratch

## Overview

This project implements core machine learning algorithms from scratch using NumPy, without relying on high-level libraries such as scikit-learn or TensorFlow.

The project covers three fundamental areas of machine learning:

* Regression (Linear Regression and Elastic Net)
* Classification (Support Vector Machines)
* Neural Networks (Multi-Layer Perceptron)

## Objectives

* Understand the mathematical foundations of machine learning models
* Implement optimisation techniques such as gradient descent
* Evaluate model performance on real-world datasets

## Datasets

* **Abalone Dataset** – Predicting age from physical measurements
* **Mushroom Dataset** – Classifying mushrooms as poisonous or edible
* **Fashion Dataset** – Image-based classification task

## Methods

### Regression

* Linear regression using maximum likelihood estimation
* Elastic Net regularisation combining L1 and L2 penalties
* Cross-validation for hyperparameter tuning

### Classification

* Linear Support Vector Machine (SVM)
* Stochastic Gradient Descent (SGD) optimisation
* Kernel methods (Radial and Sigmoid kernels)

### Neural Networks

* Multi-layer perceptron (MLP)
* ReLU activation functions
* Exploration of learning rates and convergence behaviour

## Results

* Linear regression showed limited performance on nonlinear data
* Elastic Net improved generalisation through regularisation
* SVM achieved strong classification accuracy on structured data
* Neural network performance was highly sensitive to learning rate selection

## Project Structure

```id="9rj1mv"
├── data/
├── notebooks/
├── src/
├── requirements.txt
└── README.md
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/machine-learning-from-scratch.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:
   Open `notebooks/ml_models.ipynb`

## Technologies Used

* Python
* NumPy
* pandas
* matplotlib

## Future Improvements

* Implement full backpropagation for neural networks
* Add more robust hyperparameter tuning
* Compare results with scikit-learn implementations

## Author

Dipayan Chowdhury

