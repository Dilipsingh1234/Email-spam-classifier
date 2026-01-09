**Email Spam Classifier**
**Overview**

This project builds a supervised machine learning model to classify emails as spam or non-spam using high-dimensional word-frequency features. Multiple classifiers are evaluated to identify the most reliable and interpretable approach.

**Dataset**

Kaggle Email Spam Classification Dataset

5,172 emails

~3,000 numerical word-frequency features

Binary target: spam / not spam

**Approach**

80/20 train–test split

Feature scaling using StandardScaler

Class imbalance handling with SMOTE

Model comparison across multiple classifiers

**Models Evaluated**

Logistic Regression

Random Forest

Naïve Bayes

XGBoost

Support Vector Machines (Linear, RBF, Polynomial)

Dimensionality reduction techniques (PCA, Kernel PCA, LDA) were tested but did not improve performance.

**Final Model & Results**

Final Model: Logistic Regression

Accuracy: ~96%

Strong generalization and interpretability without dimensionality reduction

**Tech Stack**

Python, NumPy, Pandas, Scikit-learn

**Key Takeaway**

Classical machine learning models with proper preprocessing can achieve high performance in email spam detection without deep learning.
