# 🤖 ml-repo

> **Welcome to ml-repo!**
> Explore machine learning concepts step by step — one import, one technique, one dataset at a time.

This is a hands-on ML learning journal. Each notebook isolates a concept, algorithm, or dataset so the ideas stay clear and the code stays readable. Built with scikit-learn, PyTorch, and Python.

---

## 📂 Notebook Index

### 🔥 PyTorch Fundamentals

| # | Notebook | Topics |
|---|----------|--------|
| 101 | [101 torch.ipynb](101%20torch.ipynb) | PyTorch tensors, operations, autograd basics |
| 102 | [102 torch.ipynb](102%20torch.ipynb) | Building and training simple neural networks |

---

### 📐 Scikit-learn — Concepts & Reference

| # | Notebook | Topics |
|---|----------|--------|
| 103 | [103 Scikit Data Leakage, Pipe, degree, corr.md](103%20Scikit%20Data%20Leakage%2C%20Pipe%2Cdegree%2C%20corr.md) | Data leakage, pipelines, polynomial degree, correlation |

---

### 📈 Regression

| # | Notebook | Dataset | Techniques |
|---|----------|---------|------------|
| 104 | [104 scikit regression diabetes dataset.ipynb](104%20scikit%20regression%20diabetes%20dataset.ipynb) | Diabetes (sklearn) | Linear Regression, baseline models |
| 105 | [105 scikit regression Fuel cons.ipynb](105%20scikit%20regression%20Fuel%20cons.ipynb) | Fuel Consumption | Linear Regression, feature analysis |
| 106 | [106 California Housing LinReg RF.ipynb](106%20California%20Housing%20LinReg%20RF.ipynb) | California Housing | Linear Regression, Random Forest |
| 107 | [107 California housing Poly feat regularization.ipynb](107%20California%20housing%20Poly%20feat%20regularization.ipynb) | California Housing | Polynomial Features, Ridge, Lasso |
| 111 | [111 KNN regr california housng.ipynb](111%20KNN%20regr%20california%20housng.ipynb) | California Housing | KNN Regression, hyperparameter tuning |

---

### 🎯 Classification

| # | Notebook | Dataset | Techniques |
|---|----------|---------|------------|
| 108 | [108 Log reg hearing_test.ipynb](108%20Log%20reg%20hearing_test.ipynb) | Hearing Test | Logistic Regression, binary classification |
| 109 | [109 Log reg iris dataset.ipynb](109%20Log%20reg%20iris%20dataset.ipynb) | Iris (sklearn) | Logistic Regression, multiclass |
| 110 | [110 KNN Classifier -breast cancer dataset.ipynb](110%20KNN%20Classifier%20-breast%20cancer%20dataset.ipynb) | Breast Cancer Wisconsin | KNN Classifier, scaling, best-k selection |
| 112 | [112 KNN classifier gene expression.ipynb](112%20KNN%20classifier%20gene%20expression.ipynb) | Gene Expression | KNN Classifier, high-dimensional data |
| 113 | [113 Decision tree iris dataset.ipynb](113%20Decision_tree_iris_dataset.ipynb) | Iris (sklearn) | Decision Tree, KNN, Logistic Regression, GridSearchCV, CV comparison |
---

## 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-orange?logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-ee4c2c?logo=pytorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

**Core libraries used across notebooks:**

```
scikit-learn   — models, pipelines, preprocessing, metrics
PyTorch        — tensors
pandas         — data loading and manipulation
numpy          — numerical operations
matplotlib / seaborn — visualization
```

---

## 🗺️ Learning Path

The notebooks follow a deliberate progression:

```
PyTorch basics (101–102)
    ↓
Scikit-learn concepts — pipelines, leakage (103)
    ↓
Regression — Linear → Polynomial → Regularization → KNN (104–107, 111)
    ↓
Classification — Logistic Regression → KNN (108–110, 112)
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/joamonf/ml-repo.git
cd ml-repo
pip install scikit-learn torch pandas numpy matplotlib seaborn jupyter
jupyter notebook
```

---

## 📌 About

This repo is a personal ML study log — each notebook is a focused experiment, not a polished production pipeline. The goal is depth over breadth: understand *why* something works before moving on.

---

*More notebooks added as the journey continues.*
