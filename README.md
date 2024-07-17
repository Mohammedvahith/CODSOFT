# CodSoft Internship

Welcome to the CodSoft Internship repository. This repository contains the tasks completed during my internship at CodSoft. Each task involves developing machine learning models for different real-world applications. Below you will find detailed information about each task, including the methods and technologies used.

## Table of Contents

- [Overview](#overview)
- [Tasks](#tasks)
  - [Task 1: Movie Genre Classification](#task-1-movie-genre-classification)
  - [Task 2: Credit Card Fraud Detection](#task-2-credit-card-fraud-detection)
  - [Task 3: Customer Churn Prediction](#task-3-customer-churn-prediction)
  - [Task 4: Spam SMS Detection](#task-4-spam-sms-detection)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository showcases the work done during my internship at CodSoft. The tasks involve building and evaluating machine learning models for various applications. Each task is implemented in a Jupyter Notebook, providing a detailed, step-by-step approach to solving the problem.

## Tasks

### Task 1: Movie Genre Classification

**File:** `Task_1(Movie_Genre_Classification).ipynb`

**Description:** This task involves developing a machine learning model to classify movies into different genres based on their descriptions. The dataset used includes movie plots and corresponding genres. Various natural language processing techniques and classification algorithms were employed to achieve high accuracy.

**Techniques Used:**
- Natural Language Processing (NLP)
- Bag of Words (BoW)
- Term Frequency-Inverse Document Frequency (TF-IDF)
- Classification Algorithms: Logistic Regression, Random Forest, Support Vector Machine (SVM)

**Process:**
1. **Data Preprocessing:** Clean and preprocess the text data (movie plots).
2. **Feature Extraction:** Use BoW and TF-IDF to convert text data into numerical features.
3. **Model Training:** Train multiple classification models to predict the genre.
4. **Evaluation:** Evaluate the models using metrics such as accuracy, precision, recall, and F1-score.
5. **Hyperparameter Tuning:** Optimize the model using techniques such as Grid Search and Cross-Validation.

### Task 2: Credit Card Fraud Detection

**File:** `Task_2(CREDIT_CARD_FRAUD_DETECTION).ipynb`

**Description:** This task focuses on detecting fraudulent credit card transactions. The dataset contains transaction details labeled as fraudulent or legitimate. The goal is to build a model that accurately identifies fraudulent transactions.

**Techniques Used:**
- Data Preprocessing
- Feature Engineering
- Handling Imbalanced Data: SMOTE (Synthetic Minority Over-sampling Technique)
- Classification Algorithms: Decision Trees, Random Forest, XGBoost

**Process:**
1. **Data Exploration:** Visualize and understand the distribution of the data.
2. **Handling Imbalanced Data:** Use SMOTE to balance the dataset.
3. **Feature Engineering:** Create new features to improve model performance.
4. **Model Training:** Train various classification models to detect fraud.
5. **Evaluation:** Evaluate models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
6. **Model Improvement:** Tune hyperparameters and ensemble methods 
