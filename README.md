# Alzheimer’s Risk Prediction  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AnayJha/Alzheimers-Risk-Prediction/blob/main/alzheimers_risk_prediction.ipynb)

This project demonstrates how **machine learning** can be applied to **genetic variant data** to predict disease risk. Using ClinVar-filtered Alzheimer’s-related SNPs, synthetic genotype data was generated for 1,000 individuals and analyzed to identify genetic markers influencing risk.

##  Overview  
We focused on **383 unique SNPs** associated with Alzheimer’s disease, simulating genotype profiles for both at-risk and non-risk individuals. Machine learning models were then trained to classify risk status based on the SNP data.

##  Workflow  
1. **Data Preparation** – Filtered ClinVar for Alzheimer’s-associated SNPs and generated synthetic genotype data.  
2. **Feature Analysis** – Applied **Principal Component Analysis (PCA)** for visualization and **Random Forest feature importance** to rank SNP significance.  
3. **Model Training** – Trained **Logistic Regression** and **Random Forest** classifiers.  
4. **Evaluation** – Evaluated performance metrics and visualized SNP contributions with ROC curves and SHAP values.

##  Tools & Libraries  
- **Python**, especially `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `shap`  
- ClinVar database (for SNP filtering)  
- Google Colab (for cloud execution and easy reproducibility)

##  Key Results  
- Identified top influential SNPs contributing to Alzheimer’s risk prediction.  
- Demonstrated strong separation between at-risk and non-risk individuals in the PCA.  
- Showcased the utility of interpretable ML (feature importance, SHAP) in genetic risk prediction.

---

Want to tweak any section—like adding a dataset explanation or modifying an icon? Just let me know!
