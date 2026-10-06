# Python & Machine Learning

My personal learning repository, following the GeeksforGeeks tutorials. Every topic gets its own notes, code examples or small projects.

> The notes and explanations were written mostly in my native language (Hungarian) to speed up my own learning process and to acquire a deep foundational knowledge.

## Table of Contents

- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Progress](#progress)
- [Projects](#projects)
- [Resources](#resources)

## Repository Structure

```
ds-learning-journey/
├── README.md
├── .gitignore
├── 01-python/
│   ├── 01-basics/
│   ├── 02-functions/
│   ├── 03-data-structures/
│   ├── 04-oop/
│   ├── 05-exceptions-files/
│   ├── 06-databases/
│   ├── 07-libraries/
│   └── 08-projects/
└── 02-machine-learning/
    ├── 01-fundamentals/
    ├── 02-math/
    ├── 03-data-preparation/
    ├── 04-eda/
    ├── 05-supervised/
    ├── 06-evaluation/
    ├── 07-unsupervised/
    ├── 08-reinforcement/
    ├── 09-semi-self-supervised/
    ├── 10-time-series/
    ├── 11-deployment-mlops/
    └── 12-projects/
```

## Getting Started
 
Windows setup (PowerShell):
 
```powershell
git clone https://github.com/vojcsektunde/ds-learning-journey.git
cd ds-learning-journey
 
py -3.13 -m venv .venv
.venv\Scripts\Activate.ps1
 
python -m pip install --upgrade pip
pip install numpy pandas matplotlib seaborn scipy statsmodels scikit-learn xgboost jupyterlab

jupyter lab
```

Install these later, when you reach the topic:
 
```powershell
pip install pymongo mysql-connector-python         # Databases
pip install streamlit gradio flask fastapi uvicorn  # Deployment and MLOps
```
 
- If PowerShell blocks the activation script, run this once:
  `Set-ExecutionPolicy -Scope CurrentUser RemoteSigned`
- In Command Prompt (cmd) use `.venv\Scripts\activate.bat` instead.
  
**Python version:** 3.13

## Progress

### Part #1 – Python

- Basics (variables, operators, data types, conditional statements, loops)
- Functions (lambda, map/filter/reduce, decorators, recursion)
- Data Structures (string, list, tuple, dict, set, collections)
- OOP (classes, inheritance, polymorphism, iterators)
- Exception Handling
- File Handling (os, pathlib)
- Databases (MySQL, MongoDB)
- Packages and Libraries
- Data Science Libraries (NumPy, Pandas, Matplotlib, Seaborn)

### Part #2 – Machine Learning

1. ML Basics (AI vs ML vs DL, ML workflow)
2. Python for ML (→ see Part 1)
3. Mathematics (probability, statistics, linear algebra, gradient descent)
4. Data Preprocessing (cleaning, missing values, scaling, feature engineering)
5. Exploratory Data Analysis (EDA)
6. Supervised Learning (linear/logistic regression, decision tree, KNN, Naive Bayes, SVM, ensemble, Random Forest)
7. Model Evaluation and Optimization (confusion matrix, ROC, cross-validation, hyperparameter tuning)
8. Unsupervised Learning (clustering, PCA, anomaly detection)
9. Reinforcement Learning (MDP, Q-learning, SARSA)
10. Semi-supervised and Self-supervised Learning
11. Time Series and Forecasting (ARIMA, SARIMA)
12. Deployment and MLOps (Streamlit, Gradio, Flask, FastAPI)

## Projects

> not started 

## Resources

- [GeeksforGeeks – Python Tutorial](https://www.geeksforgeeks.org/python/python-programming-language-tutorial/)
- [GeeksforGeeks – Machine Learning Tutorial](https://www.geeksforgeeks.org/machine-learning/machine-learning-tutorial/)

