# **Parkinson's Disease Detection Model**

This repository contains a Jupyter Notebook implementing a machine learning model for detecting Parkinson's Disease using various classification techniques. The notebook covers data preprocessing, feature engineering, model training, and evaluation, providing a comprehensive workflow for predicting Parkinson's Disease from patient data.

### **Overview**
Parkinson's Disease is a degenerative disorder of the central nervous system that affects movement. Early detection can significantly improve patient outcomes. This project leverages machine learning to analyze patient data and predict the presence of Parkinson's Disease.

### **Key Features**
Data Preprocessing: Includes normalization using MinMaxScaler, and handling imbalanced datasets with techniques like Random OverSampling.
Feature Engineering: Utilizes Principal Component Analysis (PCA) to reduce the dimensionality of the dataset while retaining 95% of the variance.
Model Training: Multiple classifiers are applied, including XGBoost, with performance measured through metrics such as accuracy, precision, recall, and F1 score.
Evaluation: Visualizes model performance using ROC curves and confusion matrices to assess the predictive accuracy of the classifiers.

### **Results**
The models are evaluated on their ability to correctly classify patients, with the XGBoost classifier showing promising results in terms of accuracy and AUC scores.

### **Conclusion**
This project demonstrates the potential of machine learning in medical diagnosis, specifically for Parkinson's Disease. Future work could involve exploring deeper neural networks or other advanced techniques for even more accurate predictions.

### **License**
This project is licensed under the MIT License.
