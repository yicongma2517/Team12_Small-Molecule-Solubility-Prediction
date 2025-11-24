# CHE1147 Team 12: Small Molecule Solubility Prediction

This repository is created for **CHE1147 Team 12 Machine Learning project** on **small molecule solubility prediction**.

---

## Project Objective

The main project objective is to develop machine learning models capable of accurately predicting the solubility of a small molecule in different solvents and under various temperatures. The molecule chosen for this project is **flutamide**. Three regression models were developed:

* **Linear Regression** (baseline)
* **Random Forest**
* **XGBoost**

---

## Data Source

The raw solubility data used for ML model training was extracted from [Chemixhub](https://github.com/chemcognition-lab/chemixhub/tree/main/datasets/drug-solubility/processed_data).

---

## Notebook Files

1. **EDA_Main_v5.ipynb** – Pulls and preprocesses flutamide solubility measurements and examines the distribution of raw data.
2. **ML_Main_v1.ipynb** – Performs training, testing, tuning, and evaluation of the three ML models.

---

## Environment Replication

A `requirements.txt` file is included to facilitate environment replication.

### Using pip:

```bash
# Create virtual environment
python -m venv .venv
# Activate the environment
# Windows
.\.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
# Install dependencies
pip install -r requirements.txt
```

> This ensures that all necessary Python packages are installed to run the notebooks.

---

## How to Run Training and Analysis

1. Activate the environment (see above).
2. Open **EDA_Main_v5.ipynb** to explore and preprocess the dataset.
3. Open **ML_Main_v1.ipynb** to train, tune, and evaluate the three ML models.

All results, figures, and model outputs will be generated within the notebooks.

---

## Notes

* Ensure Python version is compatible with the `requirements.txt` packages (Python 3.13 recommended).
* For reproducibility, use the exact versions listed in `requirements.txt`.
* The notebooks can be run in Jupyter Notebook or VS Code with the Python extension.

