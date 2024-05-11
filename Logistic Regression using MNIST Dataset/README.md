[![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg?style=flat&logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3110/)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit_learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/)

 ----
# Binary Classification of 0's and 1's in MNIST Dataset using Logistic Regression 


This repository contains a Python implementation of a logistic regression model used to classify images of digits 0 and 1 from the MNIST dataset. The code demonstrates the process of loading the dataset, preprocessing, training a logistic regression model, and evaluating its performance.

## Overview

The MNIST dataset is one of the most common datasets used for image classification. Logistic regression, despite its simplicity, can achieve reasonably high accuracy in binary classification tasks. This project specifically focuses on distinguishing between the digits 0 and 1 from the MNIST dataset.

## Dataset

The MNIST dataset used in this project can be downloaded from the following link:

[Download MNIST dataset](https://www.openml.org/data/download/52667/mnist_784.arff)

The dataset comprises 70,000 images of handwritten digits, each image being 28x28 pixels. For the purpose of this project, only images of the digits 0 and 1 are considered, simplifying the classification task to a binary problem.

## Requirements 





- Python 3.11

- Pandas

- NumPy

- Scikit-learn

## Installation

Clone this repository to your local machine using:

```bash

git clone https://github.com/yourusername/mnist-binary-classification.git

```

Navigate into the project directory:

```bash

cd mnist-binary-classification

```

Install the required packages:

```bash

pip install -r requirements.txt

```

## Usage

Run the script `logistic_regression.py`:

```bash

python logistic_regression.py

```

This will train the logistic regression model on the MNIST dataset and output the accuracy and a classification report to the terminal.

## Project Files

- `logistic_regression.py`: The main Python script containing the code for loading the dataset, preprocessing, training the logistic regression model, and evaluating its performance.

## Results

The logistic regression model achieved an accuracy of approximately XX% on the test set. Here is a detailed classification report showcasing precision, recall, f1-score, and support for each class:

```

              precision    recall  f1-score   support

           0       0.XX      0.XX      0.XX       XXX

           1       0.XX      0.XX      0.XX       XXX

    accuracy                           0.XX      XXXX

   macro avg       0.XX      0.XX      0.XX      XXXX

weighted avg       0.XX      0.XX      0.XX      XXXX

```

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.
- **Rugved Jalit** - *Initial work* - [rugvedjalit](https://github.com/rugvedjalit)

## Acknowledgments

- The MNIST dataset is provided by Yann LeCun and Corinna Cortes via the OpenML platform.

- Scikit-learn team for their efficient tools for machine learning in Python.

---
