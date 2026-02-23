# Statistical Learning & Experimental Design Dashboard

A comprehensive analytical workbench built with **Python** and **Dash**. This project integrates advanced statistical methods, computational Design of Experiments (DOE), and regularized Machine Learning models into an interactive interface.

## 🚀 Overview
This dashboard was developed to bridge the gap between theoretical statistics and practical data application. It allows users to perform hypothesis testing, explore resampling methods, and tune regularization hyperparameters in real-time.

## 🛠️ Tech Stack
* **Frontend:** Dash (Plotly)
* **Modeling:** Scikit-learn, Statsmodels
* **Data Processing:** Pandas, NumPy
* **Inference:** SciPy (Statistical Tests)

## 📊 Key Features
* **Statistical Inference:** Implementation of **Welch’s t-test** and **Bootstrap** methods for mean difference analysis.
* **Regularized Regression:** **Ridge Regression** with dynamic $\alpha$ tuning to explore the bias-variance tradeoff.
* **Classification:** **Logistic Regression** with adjustable decision thresholds and $C$ regularization parameters.
* **DOE & Simulation:** Automated generation of synthetic student datasets (`dataset_estudiantes.csv`) for controlled experimental scenarios.

## 📂 Project Structure
* `app.py`: Main entry point. Contains the Dash layout and reactive callbacks.
* `analysis.py`: Core logic for modeling, metrics calculation, and statistical functions.
* `dataset.py`: Data generation script for creating reproducible synthetic environments.
* `requirements.txt`: List of Python dependencies.
* `Procfile` & `runtime.txt`: Configuration for deployment (Heroku/Binder).

## 💻 How to Run

### 1. Clone the repository
```bash
git clone [https://github.com/DSMichael94/statistical-learning-dashboard.git](https://github.com/DSMichael94/statistical-learning-dashboard.git)
cd statistical-learning-dashboard
