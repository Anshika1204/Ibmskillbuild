# Employee Salary Prediction using Machine Learning

## Overview

This project focuses on predicting employee income levels using Machine Learning techniques. The model is trained on the Adult Income Dataset and classifies whether an individual's income exceeds a certain threshold based on demographic and employment-related attributes.

The project includes:
- Data preprocessing
- Handling missing values
- Outlier detection and removal
- Feature encoding
- Data normalization
- Machine Learning model training
- Performance evaluation
- Visualization of results

---

## Dataset

The project uses the **Adult Income Dataset**, which contains information such as:

- Age
- Workclass
- Education
- Occupation
- Marital Status
- Relationship
- Race
- Gender
- Hours per Week
- Capital Gain/Loss
- Native Country
- Income

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Machine Learning Algorithm

The following algorithm was used:

- Random Forest Classifier

---

## Project Workflow

### 1. Data Loading
- Imported dataset using Pandas.

### 2. Data Cleaning
- Handled missing values represented by `?`.
- Removed irrelevant categories.
- Removed redundant features.

### 3. Outlier Detection
- Used boxplots to detect outliers.
- Removed extreme values from numerical features.

### 4. Feature Encoding
- Applied Label Encoding on categorical features.

### 5. Feature Scaling
- Used MinMaxScaler for normalization.

### 6. Train-Test Split
- Split dataset into training and testing sets.

### 7. Model Training
- Trained Random Forest Classifier on training data.

### 8. Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix
- F1-Score Visualization

---

## Results

The Random Forest Classifier achieved high prediction accuracy on the testing dataset and performed well in classifying income categories.

Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-Score

---

## Visualizations

The project includes:
- Boxplots for outlier detection
- Confusion Matrix Heatmap
- F1-Score Bar Graph

---
