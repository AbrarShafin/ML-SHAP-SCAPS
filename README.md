# 🚀 ML–SHAP–SCAPS Framework  
### Machine Learning–Driven Optimization of Stacked-Absorber Solar Cells  

[![DOI](https://img.shields.io/badge/DOI-10.1088%2F1361--6463%2Fae571c-blue)](https://doi.org/10.1088/1361-6463/ae571c)
[![Journal](https://img.shields.io/badge/Journal-Journal%20of%20Physics%20D-red)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Published-success)]()

---

## 📌 Overview
This repository accompanies the published research:

> **“Machine learning-aided modeling and absorption optimization in stacked-absorber heterojunction solar cells”**  
> *Journal of Physics D: Applied Physics (2026)*  

It provides a **reproducible machine learning pipeline** integrating:

- ⚡ **SCAPS-1D simulations**  
- 🤖 **Machine Learning models**  
- 🔍 **SHAP explainability analysis**  

The goal is to enable **transparent, interpretable, and high-performance modeling** of advanced solar cell structures.

---

## 🧠 Framework Pipeline

```mermaid
flowchart LR
    A[SCAPS-1D Simulation] --> B[Dataset Generation]
    B --> C[Data Preprocessing]
    C --> D[ML Model Training]
    D --> E[Model Evaluation]
    E --> F[SHAP Analysis]
    F --> G[Insight & Optimization]

---

## 📂 Contents

### Dataset/
Includes all simulation datasets (Excel/CSV) used for model training and evaluation.

### ML_codes/
Python scripts covering:
- Machine learning model development  
- Performance evaluation  
- SHAP-based interpretability analysis  

### figures/
Contains all plots and visual outputs presented in the published article.

---

## ⚠️ Note on Execution
The codes are shared for **research transparency and reference purposes**.

Due to environment-specific configurations (e.g., SCAPS-1D simulation setup, directory structures, and dependencies), modifications may be required prior to execution.

---

## 🔍 Method Summary
- Data generated using **SCAPS-1D simulations**  
- Machine learning models applied for predictive modeling  
- SHAP analysis used for model interpretability and feature importance  

---

## 📎 Citation
If you use this work, please cite:

**Kazi Abrar Shafin, Md Alamin Hossain Pappu, Ahnaf Tahmid Abir, Abdul Kuddus, Shinichiro Mouri, and Jaker Hossain (2026)**  
*Machine learning-aided modeling and absorption optimization in stacked-absorber heterojunction solar cells*  
**Journal of Physics D: Applied Physics, Volume 59, 155103**  
https://doi.org/10.1088/1361-6463/ae571c  

---

## 👥 Authors & Affiliations

**Kazi Abrar Shafin¹, Md. Alamin Hossain Pappu¹², Ahnaf Tahmid Abir³, Abdul Kuddus⁴, Shinichiro Mouri⁴⁵, and Jaker Hossain¹\***

¹ Photonic & Advanced Materials Laboratory, Department of Electrical and Electronic Engineering,  
University of Rajshahi, Rajshahi 6205, Bangladesh  

² Department of Computer Science & Engineering,  
Varendra University, Rajshahi 6204, Bangladesh  

³ Department of Computer Science & Engineering,  
East West University, Dhaka 1212, Bangladesh  

⁴ Ritsumeikan Global Innovation Research Organization,  
Ritsumeikan University, Shiga 525-8577, Japan  

⁵ Department of Electrical and Electronic Engineering, Graduate School of Science and Engineering,  
Ritsumeikan University, Shiga 525-8577, Japan  

---

## 📜 License
This repository is released under the **MIT License**.

---

## 🔗 Repository Link
https://github.com/AbrarShafin/ML-SHAP-SCAPS
