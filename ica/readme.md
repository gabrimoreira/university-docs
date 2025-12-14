# Applied Computational Intelligence (ICA) - Coursework

This directory contains technical reports and assignments developed during the **Applied Computational Intelligence** (*Inteligência Computacional Aplicada*) course at the Federal University of Ceará (UFC)

The projects focus on the practical application of Machine Learning algorithms, statistical analysis, and data preprocessing techniques using real-world datasets.

## Assignments Overview

### 1. Exploratory Data Analysis (EDA) - Wine Quality
**File:** `ICA_HW1_CDGI.pdf`

This study performs a comprehensive exploratory analysis on the "Wine Quality" dataset (Red and White wines from Portugal). The goal was to understand variable distributions, correlations, and their impact on wine quality before modeling.

* **Key Techniques:**
    * Univariate, Bivariate, and Multivariate Analysis.
    * Statistical Moments (Mean, Skewness, Standard Deviation).
    * Correlation Heatmaps (Pearson) and Scatter Plots.
    * **Principal Component Analysis (PCA):** Dimensionality reduction and variance analysis (Scree plots, Biplots).
* **Main Insights:** Analysis of chemical properties such as acidity, pH, sugar, and sulfur dioxide levels in distinguishing wine types.

### 2. Regression Models - Solubility Prediction
**File:** `ICA_HW2_CDGI-1.pdf`

This project applies and compares different regression models to predict chemical solubility based on molecular structure descriptors. The dataset consists of 228 predictors and 1267 observations.

* **Models Implemented:**
    * Ordinary Least Squares (OLS) Linear Regression.
    * **Ridge Regression** (L2-Regularization) with Cross-Validation for hyperparameter tuning ($\lambda$).
    * **Partial Least Squares (PLS)** for dimensionality reduction in regression.
    * **Neural Networks (MLP):** Multilayer Perceptron with Backpropagation.
* **Methodology:**
    * Data preprocessing using **Box-Cox transformation** to reduce skewness.
    * Performance evaluation using **RMSE** (Root Mean Squared Error) and **$R^2$** metrics via K-Fold Cross-Validation.
    * Bias-Variance trade-off analysis.

### 3. Classification Models - Grant Applications
**File:** `HW3_ICA_CDGI.pdf`

This assignment evaluates classification algorithms to predict the success of grant applications at the University of Melbourne. The study handles a high-dimensional dataset ($D=1882$) reduced for analysis.

* **Models Implemented:**
    * **Logistic Regression:** Binary classification with gradient descent.
    * **K-Nearest Neighbors (KNN):** Comparison of distance metrics (Euclidean, Manhattan, Chebyshev, Minkowski).
    * **Support Vector Machines (SVM):** Kernel analysis using Linear, RBF, Polynomial, and Sigmoid functions.
* **Performance Metrics:**
    * ROC Curves and AUC (Area Under the Curve).
    * Confusion Matrices.
    * Accuracy, Sensitivity (Recall), and Specificity trade-offs.

## Technologies & Tools
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib/Seaborn.
* **Environment:** Google Colab / Jupyter Notebooks.

## Authors
* Cícero Oliveira da Silva Júnior
* David Lima dos Santos
* Gabriel Moreira de Andrade
* Igor Pereira Gouveia
