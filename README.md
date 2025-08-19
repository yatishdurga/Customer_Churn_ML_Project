# Customer Churn Prediction (Telco) — Machine Learning

Predict customer churn for a telecom dataset using a clear, end-to-end ML workflow in a single Jupyter notebook.

> **What you get**
> - A ready-to-run notebook for EDA → preprocessing → modeling → evaluation  
> - The Telco churn dataset included in the repo  
> - Simple, reproducible steps to get results locally

---

## 1) Quick Start

```bash
# 1) Clone
git clone https://github.com/yatishdurga/Customer_Churn_ML_Project.git
cd Customer_Churn_ML_Project

# 2) (Recommended) Create & activate a virtual environment
# — Mac/Linux
python3 -m venv .venv && source .venv/bin/activate
# — Windows (PowerShell)
python -m venv .venv; .\.venv\Scripts\Activate.ps1

# 3) Install dependencies
pip install -U pip
pip install -r requirements.txt  # if you add one (see below)
# Or install the essentials:
pip install numpy pandas scikit-learn matplotlib seaborn jupyter

# 4) Launch Jupyter
jupyter notebook  # or: jupyter lab

# 5) Open & run
# Open: Customer_Churn_Prediction_using_ML.ipynb
# Run cells top → bottom (Kernel > Restart & Run All)


## 📒 Workflow

### 🔍 EDA
- Inspect **dtypes**, missing values, and class balance  
- Visualize **churn distribution** & key feature relationships  

### 🧹 Preprocessing
- Clean numeric fields (e.g., convert text to numeric where needed)  
- Encode categorical variables (one-hot encoding)  
- Split into **train/test sets** (fixed random seed)  
- *(Optional)* Handle imbalance (e.g., class weights, SMOTE)  

### 🤖 Modeling
- Start with a **baseline model** (e.g., Logistic Regression)  
- Experiment with **tree-based / boosted models** (Random Forest, XGBoost)  
- Perform **light hyperparameter tuning** (as needed)  

### 📊 Evaluation
- Metrics: **Accuracy, Precision, Recall, F1-score, ROC-AUC**  
- Plots: **Confusion Matrix, ROC curve**  
- Analyze **feature importance / coefficients** (model-dependent)  
