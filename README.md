# HGSC-TP53-Mutation-Analysis

## 📌 Overview
This project focuses on the **computational analysis of TP53 gene mutations** in **Ovarian High-Grade Serous Carcinoma (HGSC)**.  
The goal is to identify **disease-associated mutations** using **machine learning (ML)** and **deep learning (DL)** models, supporting insights for **precision oncology**.

---

## 🔬 Research Motivation
- **TP53** is the most frequently mutated gene in human cancers.  
- In **HGSC**, TP53 mutations are nearly universal and play a critical role in tumor progression.  
- Applying AI/ML can help **classify mutations, predict pathogenicity, and guide biomarker discovery**.

---

## ⚙️ Methodology
1. **Data Preprocessing**  
   - Cleaning mutation datasets  
   - PCA for dimensionality reduction  
   - MinMax scaling and normalization  

2. **Machine Learning Models**  
   - Naïve Bayes  
   - Logistic Regression  
   - XGBoost with hyperparameter tuning  
   - AutoML (TPOT) for automated pipeline optimization  

3. **Deep Learning Models**  
   - Convolutional Neural Networks (CNNs)  
   - Graph Neural Networks (GNNs) for mutation-gene network representation  

4. **Evaluation**  
   - Stratified cross-validation  
   - Accuracy, F1-score, ROC-AUC metrics  
   - Model interpretability for biological relevance  

---

## 🚀 Features
- Comparative performance of classical ML vs. advanced DL models  
- Automated pipeline search with **AutoML (TPOT)**  
- Interpretable framework for **oncology insights**  
- End-to-end Jupyter/Colab workflow  

---

## 📊 Results
- Improved classification accuracy across ML and DL pipelines  
- CNN and GNN models showed strong generalization for mutation classification  
- AutoML discovered optimized pipelines outperforming baselines  

---

## 💻 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/HGSC-TP53-mutation-analysis.git
   cd HGSC-TP53-mutation-analysis
