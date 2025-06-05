# Python Machine Learning

## Description
This repository contains a Python-based machine learning project that analyzes client data to build and evaluate predictive models. It includes a Jupyter notebook (`main.ipynb`) alongside two data files (`clientes.csv` and `novos_clientes.csv`).

The notebook handles the full workflow:
- Data loading and preprocessing,
- Model training (e.g., Decision Trees, Random Forest),
- Evaluation,
- Prediction for new client data.

The focus is on demonstrating an end-to-end machine learning pipeline.

---

## How to Run

1. **Install dependencies:**  
Make sure Python is installed. Install required libraries using:

```bash
pip install pandas scikit-learn matplotlib
(If visualizations are needed, also install:)

bash
Copiar
Editar
pip install plotly
Open the notebook:
Launch main.ipynb using Jupyter Notebook or JupyterLab.

Run the cells:
Execute each cell in sequence to:

Load CSV data,

Preprocess (encode categories, scale if needed),

Train models,

Evaluate results.

Check the output:
View the console outputs or generated plots to review:

Model performance metrics,

Predictions for novos_clientes.csv.

Features
Data Loading & Cleaning:
Handles CSV import and manages missing or inconsistent data.

Categorical Encoding:
Transforms categorical features (e.g., profession, credit mix) using Label Encoding or One-Hot Encoding.

Feature Selection & Scaling:
Selects relevant columns and applies scaling/normalization when necessary.

Model Training:
Trains multiple classifiers like Decision Tree, Random Forest, and K-Nearest Neighbors (KNN).

Evaluation Metrics:
Computes accuracy and other metrics to compare models.

Result Presentation:
Displays comparisons using tables and/or plots.

Technologies
Python: Programming language for data processing and ML.

Jupyter Notebook: Interactive coding environment.

Pandas & NumPy: Data manipulation and numeric operations.

Scikit-learn: Machine learning models and preprocessing tools.

Matplotlib & Plotly: Data visualization.

Git: Version control for the repository.

Learnings
Decision Trees:
Learn how trees split data using simple rules. Easy to interpret but prone to overfitting.

Random Forest:
Understand how ensembles of decision trees improve generalization, reducing overfitting, at the cost of interpretability and performance overhead.

Data Preprocessing:
Grasp the importance of:

Encoding categorical variables,

Scaling numerical features,

Cleaning datasets.

Train/Test Split:
Realize the necessity of splitting data to avoid data leakage and ensure accurate evaluation.

Model Evaluation:
Compare models based on accuracy (or other metrics) and understand how different algorithms perform on the same problem.


