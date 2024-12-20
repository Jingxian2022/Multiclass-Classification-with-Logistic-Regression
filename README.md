# Multiclass-Classification-with-Logistic-Regression
## Overview
This project implements multiclass classification using Logistic Regression from scratch in Python. Two popular strategies for handling multiclass problems are implemented:

- One-vs-All (OvA): Each class is trained against all others.
- All-Pairs (OvO): Binary classifiers are trained for all pairs of classes.

The implementation uses Stochastic Gradient Descent (SGD) for training and is designed to be efficient and customizable. This repository allows you to train, test, and compare the performance of these strategies on any dataset with reproducible results.

## Installation
To reproduce the results, ensure you have Python 3.12.7 installed along with the required packages listed below. You can install these packages via the provided requirements.yaml file.

## Requirements
- Python: 3.12.7
- Numpy: 2.0.1
- Scikit-learn: 1.5.1
- Pandas: 2.2.2
- pytest: 7.4.4
- imbalanced-learn: 0.12.4



## Authors
- Allison Gao
	- Email: rui_gao@brown.edu
	- GitHub: AllisonGao
	
## License
This project is licensed under the MIT License. See the LICENSE file for details.
