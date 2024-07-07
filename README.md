# Heart Disease Classification Project

Welcome to the Heart Disease Classification project repository! This project focuses on predicting the presence of heart disease based on various medical attributes.

## Overview

The goal of this project is to build machine learning models that can accurately classify whether a patient has heart disease or not. The dataset used contains [brief description of dataset source and contents].

## Key Features

- **Exploratory Data Analysis (EDA)**: Explored the dataset to understand its structure, distributions, and relationships between variables.
  
- **Feature Engineering**: Processed and engineered features to enhance model performance and interpretability.

- **Modeling Techniques**: Employed several machine learning techniques including:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Random Forest Classifier
  
- **Model Evaluation**:
  - Utilized `train_test_split` for initial model validation.
  - Applied `cross_val_score` for cross-validation to ensure robust model performance.
  - Evaluated models using `confusion_matrix` and `classification_report` to assess accuracy and other metrics.
  - Optimized model hyperparameters using `GridSearchCV` and `RandomizedSearchCV`.

- **Performance Metrics**:
  - Analyzed model performance using ROC curves to visualize true positive rates against false positive rates.

- **Feature Importance**:
  - Investigated feature importance to understand which variables have the most significant impact on predicting heart disease.

## Project Structure

The repository structure is organized as follows:

- `notebooks/`: Jupyter Notebooks containing detailed analysis and model development steps.
- `data/`: Directory housing the dataset used in the project.
- `environment.yml`: Conda environment file specifying dependencies required to run the project.

