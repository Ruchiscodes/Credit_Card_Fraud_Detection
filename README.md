# Credit_Card_Fraud_Detection

This repository contains a machine learning model for detecting fraudulent credit card transactions using various preprocessing techniques and classification models.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)


## Introduction
Credit card fraud detection is a critical application of machine learning in the finance sector. This project focuses on identifying fraudulent transactions using a dataset that includes both legitimate and fraudulent transactions. The goal is to build a robust model that can accurately classify transactions while minimizing false positives and false negatives.

## Dataset
The dataset used in this project is a publicly available credit card transaction dataset. It contains numerical features derived from PCA transformation along with a `Class` label indicating fraud (`1`) or non-fraud (`0`).

## Preprocessing
The following preprocessing steps were applied:
- Handling imbalanced data using techniques such as SMOTE (Synthetic Minority Over-sampling Technique).
- Feature scaling using StandardScaler.
- Splitting data into training and testing sets.

## Model Training and Evaluation
Several machine learning models were trained and evaluated, including:
- Logistic Regression
- Random Forest
- Time Series Analysis
- Support Vector Machine (SVM)
- Neural Networks
- RandomUnderSampler
- SMOTE techniques

Evaluation metrics used:
- Accuracy
- Precision, Recall, and F1-score
- AUC-ROC Curve
- RFClassifier
- NBClassifier
- DNN
  

## Installation
To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the Jupyter Notebook:
```bash
jupyter notebook Credit_Card_Fraud_Detection.ipynb
```

## Results
The model achieved high accuracy and recall, effectively identifying fraudulent transactions. Detailed results and insights are available in the report.

