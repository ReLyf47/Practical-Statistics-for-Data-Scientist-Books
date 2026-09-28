# Practical Statistics for Data Scientists

This repository contains code reproductions, summaries, and detailed theoretical explanations for all chapters of the book **Practical Statistics for Data Scientists** (O'Reilly) by Peter Bruce, Andrew Bruce, and Peter Gedeck.

---

## 📋 Table of Contents

1. [Overview](https://www.google.com/search?q=%23overview&utm_source=gemini)
2. [Repository Structure](https://www.google.com/search?q=%23repository-structure&utm_source=gemini)
3. [Chapter Summaries](https://www.google.com/search?q=%23chapter-summaries&utm_source=gemini)
4. [Installation & Setup](https://www.google.com/search?q=%23installation--setup&utm_source=gemini)

---

## 📌 Overview

The goal of this project is to bridge statistical concepts with practical data science workflows using Python. Each chapter is reproduced in its dedicated Jupyter Notebook (`.ipynb`), structured into three main components:

* **Code Reproduction:** Executable Python implementations of the book's statistical routines, visualizations, and datasets.
* **Chapter Summary:** High-level takeaways outlining the practical application of each statistical method.
* **Theoretical Explanations:** Mathematical formulas, assumptions, and foundational explanations for key statistical concepts.

---

## 📁 Repository Structure

```text
.
├── PracticalStatisticsChapter1.ipynb   # Chapter 1: Exploratory Data Analysis
├── PracticalStatisticsChapter2.ipynb   # Chapter 2: Data and Sampling Distributions
├── PracticalStatisticsChapter3.ipynb   # Chapter 3: Statistical Experiments & Significance Testing
├── PracticalStatisticsChapter4.ipynb   # Chapter 4: Regression and Prediction
├── PracticalStatisticsChapter5.ipynb   # Chapter 5: Classification
├── PracticalStatisticsChapter6.ipynb   # Chapter 6: Statistical Machine Learning
├── PracticalStatisticsChapter7.ipynb   # Chapter 7: Unsupervised Learning
├── requirements.txt                    # Project dependencies
└── README.md                           # Repository documentation

```

---

## 📖 Chapter Summaries

### Chapter 1: Exploratory Data Analysis (EDA)

Covers fundamental techniques for data exploration. Topics include estimates of location (mean, median, trimmed mean, weighted mean), estimates of variability (variance, standard deviation, MAD, IQR), data distribution analysis (percentiles, boxplots, frequency tables, histograms, density plots), and relationships between two or more variables (correlation matrix, scatterplots, hexbin plots, contingency tables).

### Chapter 2: Data and Sampling Distributions

Explores sampling procedures and the theoretical foundations of statistical inference. Topics include random sampling, sampling bias, selection bias, central limit theorem (CLT), standard error, bootstrap resampling, confidence intervals, and standard theoretical probability distributions (Normal, Poisson, Exponential, Binomial, Weibull).

### Chapter 3: Statistical Experiments and Significance Testing

Focuses on A/B testing and hypothesis testing. Topics include design of experiments, null and alternative hypotheses, permutation tests, p-values, alpha levels, t-tests, ANOVA (Analysis of Variance), chi-square tests, and power/sample size calculations to prevent false discoveries (Type I and Type II errors).

### Chapter 4: Regression and Prediction

Examines linear modeling techniques used to predict numeric outputs. Topics include simple linear regression, multiple linear regression, model evaluation ($R^2$, RMSE, RSE), cross-validation, polynomial regression, spline fitting, step-wise regression, partial residual plots, and diagnostic analysis of outliers, leverage, heteroskedasticity, and multicollinearity.

### Chapter 5: Classification

Covers supervised learning algorithms for predicting binary and categorical targets. Topics include Naive Bayes classification, Discriminant Analysis (LDA), Logistic Regression (odds ratios, logit link, evaluation metrics like ROC/AUC, confusion matrices), and handling imbalanced datasets using resampling strategies (SMOTE, undersampling).

### Chapter 6: Statistical Machine Learning

Focuses on non-parametric and ensemble machine learning algorithms. Topics include K-Nearest Neighbors (KNN), Tree-based models (Decision Trees, Random Forests, Gradient Boosted Trees / XGBoost), hyperparameter tuning, and feature importance analysis.

### Chapter 7: Unsupervised Learning

Explores algorithms used to extract patterns from unlabeled datasets. Topics include Principal Component Analysis (PCA) for dimensionality reduction, K-Means clustering, Hierarchical Cluster Analysis, Model-Based Clustering (Gaussian Mixture Models), and categorical data dimension reduction.

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
```bash
git clone https://github.com/YOUR_USERNAME/Practical-Statistics-for-Data-Scientists.git
cd Practical-Statistics-for-Data-Scientists

```


2. **Set up a virtual environment (optional but recommended):**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

```


3. **Install required packages:**
```bash
pip install -r requirements.txt

```


4. **Run Jupyter Notebook:**
```bash
jupyter notebook

```
adjustText

```
