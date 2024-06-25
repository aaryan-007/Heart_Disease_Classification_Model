# End-to-End Heart Disease Classification

## Overview

This repository contains an end-to-end pipeline for classifying heart disease using machine learning techniques. The project covers data preprocessing, feature engineering, model training, evaluation, and deployment, providing a comprehensive solution for heart disease prediction.

## Introduction

Heart disease is a leading cause of death globally, and early diagnosis is crucial for effective treatment and management. This project aims to leverage machine learning to predict the presence of heart disease based on a variety of medical attributes.

## Dataset

The dataset used in this project includes several medical parameters such as age, sex, chest pain type, resting blood pressure, cholesterol level, and more. The data is preprocessed to handle missing values, categorical variables, and feature scaling.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/end-to-end-heart-disease-classification.git
    ```
2. Navigate to the project directory:
    ```bash
    cd end-to-end-heart-disease-classification
    ```
3. Create a virtual environment:
    ```bash
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
5. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Model

The notebook explores various machine learning models to tackle the given problem. Here's an overview of the models included:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* Neural Networks

Each model is rigorously evaluated using relevant metrics to identify the best performer on the test set.

## Results

The results section delves into the performance of the chosen model, providing detailed analysis of metrics like accuracy, precision, recall, F1 score, and ROC-AUC curves. 

**Best Model Performance:**

| Metric | Score |
|---|---|
| Accuracy | 84.47% |
| Precision | 82.08% |
| Recall | 92.12% |
| F1 Score | 86.73% |
| ROC-AUC | 0.93 |


This project gratefully acknowledges the following resources:

* **UCI Machine Learning Repository:** We thank the UCI Machine Learning Repository for providing the valuable dataset used in this project. Their extensive collection of datasets facilitates research and development in machine learning.
* **Scikit-learn:** We express our appreciation to the Scikit-learn project for its comprehensive suite of machine learning tools. These tools enabled us to efficiently implement and evaluate various models.
* **Matplotlib and Seaborn:** A big thanks to Matplotlib and Seaborn for their powerful visualization libraries. They were instrumental in creating insightful visualizations to explore and communicate our findings.

## Usage

Open the Jupyter notebook to explore and run the code:

```bash
jupyter notebook end-to-end-heart-dis-classification.ipynb


