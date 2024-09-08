# Handwritten Digit Classification using Logistic Regression and Custom Implementation

This project focuses on classifying handwritten digits using the well-known **MNIST dataset**. Two models are implemented:
1. A **logistic regression** model built from scratch.
2. A **Scikit-learn** implementation of logistic regression for comparison.

Both models are evaluated based on their accuracy and confusion matrices across multiple iterations.

## Project Goals

- Implement logistic regression from scratch using Python and NumPy.
- Use **Scikit-learn**'s built-in logistic regression for benchmarking.
- Compare the performance of both models in terms of accuracy and statistical metrics.
- Visualize the digits, confusion matrices, and accuracy over multiple iterations.

## Repository Contents

- **main.py**: The main script to run the models, including data loading, training, and evaluation.
- **models.py**: Contains the custom implementation of logistic regression (`nn`) and the Scikit-learn-based model (`nn_sk`).
- **visualization.py**: Functions for visualizing digits, confusion matrices, and accuracy plots.

## Requirements

To run this project, you need the following Python libraries:
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

You can install them using:
```bash
pip install numpy scikit-learn matplotlib seaborn

Running the Project
```

## Running the Project

Clone the repository:

```bash
git clone https://github.com/yourusername/handwritten-digit-classification.git
cd handwritten-digit-classification
```

Run the main script:

```bash
python main.py
```
