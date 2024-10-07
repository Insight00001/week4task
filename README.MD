# Project Description

The project explores multiple machine learning models for predicting student dropout risks, with the goal of early detection and intervention. The models are evaluated using a comprehensive set of performance metrics, including accuracy, precision, recall, F1 score, and ROC-AUC. The comparison of models is visualized for clearer interpretation of their effectiveness.
# Technologies Used
    Python 3.x
    Pandas: Data manipulation
    NumPy: Numerical computations
    Matplotlib: Data visualization
    Scikit-learn: Machine learning algorithms
    XGBoost: Gradient boosting
    TensorFlow/Keras: Neural networks
    Streamlit: Web app deployment (for EDA)

# Dataset
The dataset cleaned_data.csv contains features related to student demographics, academic records, and family background. The target variable categorizes students into three classes:

    0: Dropout
    1: Enrolled
    2: Graduate

# Features:

    Age
    Gender
    GDP
    Debtor
    Nationality

# Preprocessing

Key preprocessing steps include:
    Categorical Encoding: Mapping of categorical target variables.
    Feature Scaling: Standardization using StandardScaler to normalize feature values.
    Train/Test/Validation Split: The data is split into training (60%), testing (24%), and validation (16%) sets.

# Models Implemented

Several machine learning models were trained and evaluated:

    Logistic Regression
    Decision Tree Classifier
    Random Forest Classifier
    Support Vector Machine (SVC)
    XGBoost Classifier
    Neural Networks using TensorFlow/Keras

Each model's performance was evaluated on the training, test, and validation sets.
Performance Evaluation

The models are evaluated using several key metrics:

    Accuracy
    F1 Score
    Precision
    Recall
    ROC-AUC Score

These metrics are computed using cross-validation to ensure the models generalize well to unseen data.

# Visualization

Performance across the models is visualized using plots for better interpretation. The following metrics are plotted:

    Accuracy
    F1 Score
    Precision
    Recall
    ROC-AUC

# How to Use
Prerequisites

Install the necessary libraries:

bash

pip install pandas numpy scikit-learn xgboost tensorflow matplotlib 

# Running the Notebook

    Clone the repository:

    bash

    git clone https://github.com/Insight00001/week4task.git

    Open Modelling.ipynb in Jupyter or another notebook environment.
    Execute all cells to preprocess data, train models, and evaluate performance.

# Contributing

We welcome contributions! Please fork the repository, create a branch, and submit a pull request with improvements or bug fixes.
# License

This project is licensed under the MIT License. See the LICENSE file for details.



​