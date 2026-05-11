# Programmed Project I — Machine Learning

**Course:** IC-6200 / Artificial Intelligence  
**Institution:** Costa Rica Institute of Technology  

This repository contains an extensive practical portfolio implemented in a Jupyter notebook (`ProyectoIA.ipynb`), where three main families of Machine Learning algorithms (supervised and unsupervised) are developed, evaluated, and compared using various real-world datasets.

## Analyzed Algorithms and Datasets

### 1. Logistic Regression (Binary Classification)
Logistic regression is used to predict probabilities and classify data into two categories.
*   **Students Performance:** Prediction of whether a student passes or fails mathematics based on sociodemographic conditions and reading/writing scores.
*   **Wine Quality (White Wine Quality):** Prediction of whether a wine is of high quality based on its physicochemical characteristics, handling a dataset with class imbalance.

### 2. K-Nearest Neighbors - KNN (Classification and Regression)
Demonstration of the versatility of the KNN algorithm for both discrete and continuous problems.
*   **Netflix (Classification):** Identification of the type of content (Movie or TV Show) mainly based on genres and duration.
*   **WHO Life Expectancy (Regression):** Prediction of life expectancy in years according to health, social, and economic development indicators by country.

### 3. Clustering (Unsupervised Learning)
Data grouping without labels using **K-Means** and **GMM (Gaussian Mixture Models)** / **DBSCAN**.
*   **Credit Card Fraud Detection:** Segmentation of credit card transactions to naturally identify and detect anomalies (fraud) without using the target label during training.
*   **Telco Customer Churn:** Segmentation of telecommunications customers according to their profile and usage behavior to identify groups with different levels of service cancellation risk (churn).

## Applied Methodology

For each model implemented in the notebook, the following Data Science workflow is rigorously followed:
1. **Loading and Initial Exploration:** Understanding the variables and data structure.
2. **Exploratory Data Analysis (EDA):** Visualization of distributions, correlations, and relationships between variables.
3. **Preprocessing:** Data scaling (essential for distance-based algorithms such as KNN and K-Means), categorical variable encoding, and techniques for handling imbalance and outliers.
4. **Training and Hyperparameter Tuning:** Optimization techniques such as searching for the optimal K through cross-validation and the elbow/silhouette method for Clustering.
5. **Model Evaluation:** Result analysis using multiple metrics such as Accuracy, Precision, Recall, F1-Score, AUC-ROC, RMSE, MAE, and R² Score.

## How to Use This Project

To reproduce the analysis, open the main notebook:
```bash
jupyter notebook ProyectoIA.ipynb
```

*Note: Make sure you have the typical Python data science dependencies installed (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).*

## Author

* **Ovidio Taleno**
