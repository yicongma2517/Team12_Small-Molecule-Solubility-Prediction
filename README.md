# CHE1147 Team 12: Small Molecule Solubility Prediction

This repository is created for CHE1147 Team 12 Machine Learning project on **small molecule solubility prediction**. 

## Project Objective
The main project objective is to develop ML models capable of predicting a small molecule's solubility in different solvents and under various temperatures. The small molecule chosen for this project is **flutamide**. Three regression models were developed:
- Linear Regression (baseline)
- Random Forest
- XGBoost

## Data Source
Raw solubility data was extracted from [chemixhub](https://github.com/chemcognition-lab/chemixhub/tree/main/datasets/drug-solubility/processed_data).

## Notebook Files
1. **EDA_Main_v5.ipynb** – Pulls and preprocesses flutamide solubility measurements and examines the distribution of raw data.
2. **ML_Main_v1.ipynb** – Performs training, testing, tuning, and evaluation of the three ML models.

## Environment
A `requirements.txt` is included to facilitate environment replication for running this project.

