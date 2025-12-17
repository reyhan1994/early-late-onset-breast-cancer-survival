# early-late-onset-breast-cancer-survival
Early- vs late-onset breast cancer comparison integrating clinical, genomic features and survival analysis using classical statistics and deep learning models.
# Breast Cancer Early-onset vs Late-onset Survival Analysis

This repository presents a reproducible analysis of breast cancer gene expression
and clinical data from the METABRIC cohort, with a focus on age-of-onset–related
differences in tumor biology and patient survival.

## Project Structure

1. **Early-onset vs Late-onset Comparison**
   - Stratification of patients based on age at diagnosis
   - Comparison of clinical variables and gene expression patterns

2. **Survival Difference Between Early vs Late**
   - Kaplan–Meier survival analysis
   - Statistical comparison using log-rank tests

3. **Deep Learning–Based Representation Learning**
   - Autoencoder model trained on high-dimensional gene expression data
   - Extraction of latent representations

4. **Autoencoder + Survival Modeling**
   - Cox proportional hazards modeling in the learned latent space
   - Evaluation of prognostic value of deep representations

## Dataset
- METABRIC Breast Cancer Gene Expression dataset (Kaggle)

## Tools
Python, Pandas, Scikit-learn, PyTorch, Lifelines

## Motivation
This project demonstrates the integration of large-scale genomic data with
deep learning and survival analysis for clinical risk modeling.

