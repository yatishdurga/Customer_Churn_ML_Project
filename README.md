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
