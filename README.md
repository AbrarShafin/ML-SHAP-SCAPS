# 🚀 ML–SHAP–SCAPS Framework  
### Machine Learning–Driven Optimization of Stacked-Absorber Solar Cells  

[![DOI](https://img.shields.io/badge/DOI-10.1088%2F1361--6463%2Fae571c-blue)](https://doi.org/10.1088/1361-6463/ae571c)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📌 Overview
This repository accompanies the published research:

**"Machine learning-aided modeling and absorption optimization in stacked-absorber heterojunction solar cells"**  
*Journal of Physics D: Applied Physics, 2026*

It provides **code, dataset, and explainability tools** for a reproducible ML pipeline integrating:

- SCAPS-1D simulations  
- Machine Learning models  
- SHAP-based interpretability  

---

## 🧠 Framework Pipeline

```mermaid
flowchart LR
    A[SCAPS-1D Simulation] --> B[Dataset Generation]
    B --> C[Data Preprocessing]
    C --> D[ML Model Training]
    D --> E[Model Evaluation]
    E --> F[SHAP Analysis]
    F --> G[Physical Insight & Optimization]
