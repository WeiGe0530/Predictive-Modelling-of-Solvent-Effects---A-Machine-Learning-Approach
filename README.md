# ML-Based Prediction and Interpretation of Drug Loading in Polymer Nanoparticles
This repository contains the dataset and Python code used in the study:
**“Data-Driven Prediction and Interpretation of Drug Encapsulation and Loading Capacity in Polymer Nanoparticles”

## Overview
This project investigates the relationship between solvent physicochemical properties and nanoparticle performance (Encapsulation Efficiency, EE% and Drug Loading Capacity, DLC%) using multiple machine learning models. The final model (Multilayer Perceptron, MLP) was optimized and interpreted using SHAP (SHapley Additive exPlanations) to identify the most influential features governing drug loading outcomes.

## Repository Contents
- `data/Data.csv` – Preprocessed input dataset with physicochemical descriptors.
- `notebooks/ML_models_comparison.ipynb` – Code to train and compare RF, XGBoost, Gradient Boosting, SVR, and MLP models.
- `notebooks/MLP_hyperparameter_optimization.ipynb` – Hyperparameter tuning workflow for MLP model.
- `notebooks/SHAP_analysis.ipynb` – SHAP value computation and visualization for EE% and DLC%.


## Requirements
This project supports Python 3.7 through 3.10 and requires the following packages:
- `numpy`  
- `pandas`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  
- `shap` 

## Dataset Description
Each row represents a solvent condition used in nanoparticle formulation. Features include:
- Curcumin solubility
- Hansen solubility parameters (δd, δp, δh)
- Hildebrand parameter
- Dielectric constant
- Viscosity
- Dipole moment
- Polarity
Outputs:
- EE% (Encapsulation Efficiency)
- DLC% (Drug Loading Capacity)


## Citation
If you use this repository, please cite our paper:



