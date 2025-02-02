# Bike Sharing Dataset: Data Cleaning, Feature Engineering, and Classification Techniques

## Overview

This repository contains the solution for the Bike Sharing Dataset assignment, which is divided into two parts:

1. **Data Cleaning and Feature Engineering**
2. **Comparative Analysis of Classification Techniques**

The assignment focuses on applying data preprocessing techniques, such as handling missing values, encoding categorical variables, feature engineering, and comparing the performance of various classification techniques: Random Forest (RF), Support Vector Machine (SVM), and Multilayer Perceptron (MLP).

---

## Part 1: Data Cleaning and Feature Engineering for the Bike Sharing Dataset

### Objectives
- Explore and preprocess the dataset by addressing missing values, encoding categorical variables, and scaling numerical features.
- Apply feature selection and dimensionality reduction techniques for effective data preparation.
- Evaluate the impact of preprocessing on model performance.

### Procedure
1. **Data Exploration**: Summarize dataset statistics to understand the structure, features, and any missing values.
2. **Data Visualization**: Explore relationships between features using visualizations (box plots, scatter plots, histograms) to reveal patterns and insights.
3. **Data Cleaning**:
   - Address missing values and outliers by selecting appropriate imputation methods or removing irrelevant data.
   - Apply necessary transformations to ensure data quality.
4. **Feature Engineering**:
   - Analyze the relevance of each feature.
   - Encode categorical variables into numerical formats (e.g., one-hot encoding).
   - Scale or normalize numerical features.
   - Use dimensionality reduction techniques to retain essential information.
5. **Model Evaluation**:
   - Split the dataset into training and testing subsets.
   - Train a Random Forest model on the preprocessed data.
   - Compare performance of the model trained on preprocessed data vs. raw data.

### Experiments
- Compare the Random Forest model performance on preprocessed data and raw data.
- Analyze the impact of preprocessing on model metrics: accuracy, precision, and recall.

### Results
- Summarize model performance on preprocessed vs. raw data.
- Show improvements in accuracy, consistency, and training speed due to preprocessing.

---

## Part 2: Comparative Analysis of Classification Techniques

### Objectives
- Compare the effectiveness of Random Forest (RF), SVM, and Multilayer Perceptron (MLP).
- Study the effect of parameter tuning for each model.

### Background
In this part, we assess the performance of three classification techniques—RF, SVM, and MLP—on the dataset from Part 1. The goal is to compare model performance and determine the best-suited algorithm for predicting bike demand.

### Procedure
1. **Data Preparation**: Use the preprocessed dataset from Part 1.
2. **Model Training**:
   - Train Random Forest (RF), Support Vector Machine (SVM), and Multilayer Perceptron (MLP) models.
   - Evaluate models using training and testing datasets.
3. **Model Comparison**:
   - Analyze models based on accuracy, precision, recall, and F-Measure.
   - Compare computational efficiency and training time.
   - Investigate the effect of preprocessing on model performance.
   - Explore how model parameters affect performance.

### Experiments
- Compare performance metrics (accuracy, precision, recall) for RF, SVM, and MLP.
- Evaluate the effect of different model parameters on performance.

### Results
- Provide a summary of model performance, discussing strengths and weaknesses.
- Compare models based on prediction accuracy and computational efficiency (execution time and memory usage).
- Conclude which model provides the best balance between accuracy and computational time for this dataset.

---

## Requirements

- Python 3.x
- Libraries: 
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

