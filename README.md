##Fraud Detection Model

This repository contains a supervised machine learning model implemented in Python for detecting credit card fraud using the k-Nearest Neighbors (KNN) algorithm. Additionally, this model leverages clustering techniques such as K-Means and DBSCAN to uncover hidden trends within the data. Feature engineering techniques and cross-validation are employed to enhance the model's performance and generalization capability.

## Dataset

The dataset used for training and testing the model consists of credit card transactions, with each transaction labeled as either fraudulent or legitimate. This dataset is highly imbalanced, with a significantly smaller number of fraudulent transactions compared to legitimate ones.

## Model Architecture

The credit card fraud detection model follows the following workflow:

1. **Data Preprocessing**: The dataset is preprocessed to handle missing values, outliers, and feature scaling. Additionally, feature engineering techniques are applied to extract relevant features and enhance the discriminatory power of the model.

2. **Clustering for Hidden Trends**:
    - **K-Means**: K-Means clustering is applied to identify clusters within the dataset. This can help identify patterns and potentially uncover segments that exhibit fraudulent behavior.
    - **DBSCAN**: DBSCAN (Density-Based Spatial Clustering of Applications with Noise) is utilized to identify clusters of data points that are closely packed together, which could represent unusual patterns indicative of fraud.

3. **Supervised Learning with KNN**: The preprocessed data is used to train a k-Nearest Neighbors (KNN) classifier. KNN is a non-parametric method that classifies an unknown data point based on the majority class among its k nearest neighbors.

4. **Model Evaluation and Cross-Validation**: The model's performance is evaluated using various metrics such as accuracy, precision, recall, and F1-score. Cross-validation techniques such as k-fold cross-validation are employed to assess the model's robustness and generalization performance.
