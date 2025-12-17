# Early- vs Late-Onset Breast Cancer Analysis

This repository presents a comprehensive analysis of breast cancer patients
from the **METABRIC cohort**, focusing on **age-of-onset differences** and their
impact on tumor biology and patient survival. The project integrates **clinical data**, 
**gene expression profiles**, and **deep learning models** to uncover
age-associated genomic signatures and survival patterns.

---

## 📂 Project Structure

### 1. Early-onset vs Late-onset Comparison
- Stratification of patients into **Early-onset (≤40 years)** and **Late-onset (≥60 years)** groups
- Comparison of clinical variables and gene expression patterns
- Visualization of age-associated differences

### 2. Survival Analysis: Early vs Late
- Kaplan–Meier survival curves
- Log-rank test for statistical significance
- Cox proportional hazards modeling for quantitative survival differences

### 3. Deep Learning Representation Learning
- Autoencoder applied to high-dimensional gene expression data
- Extraction of **latent features** capturing complex genomic patterns

### 4. Autoencoder + Survival Modeling
- Survival modeling using latent representations from the autoencoder
- Assessment of prognostic value of deep learning–derived features

---

## 📊 Figures
- Visualizations of age-specific clinical and genomic differences
- Kaplan–Meier survival plots
- Latent space embeddings of gene expression data
- Differential expression analysis highlights

*(All figures are stored in the `/figures` folder)*

---

## 🧰 Tools & Libraries
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning**: Scikit-learn  
- **Deep Learning**: PyTorch  
- **Survival Analysis**: Lifelines  
- **Data**: METABRIC Breast Cancer Gene Expression dataset (Kaggle)

---

## 💡 Motivation
This project demonstrates the integration of **clinical and genomic data** 
with **machine learning and deep learning approaches** to investigate
age-related differences in breast cancer biology and survival.  
It serves as a reproducible pipeline for translational cancer research
and highlights the potential of AI-assisted prognostic modeling.

---

## 📖 How to Reproduce
1. Clone the repository  
```bash
git clone https://github.com/<your-username>/early-late-onset-breast-cancer-survival.git
```

2.Install dependencies
```
pip install -r requirements.txt
```
3.Open notebooks in /notebooks and follow the step-by-step analysis
🔗 Citation
Dataset: [METABRIC Breast Cancer Gene Expression (Kaggle)](https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric)

