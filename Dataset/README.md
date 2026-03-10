# Dataset Documentation

## Overview

This directory contains the dataset used for training, validation, and testing machine learning models developed for predicting the photovoltaic performance of stacked-absorber heterostructure solar cells.

The dataset consists of simulated device parameters and performance metrics derived from multiple combinations of absorber materials and back surface field (BSF) layers.

The data is structured to support machine learning models for predicting key photovoltaic outputs including open-circuit voltage, short-circuit current density, fill factor, and power conversion efficiency.

---

# Dataset Structure

```
Dataset
│
├── concatenated_all_final.xlsx
│
└── Dataset_For_validating
    ├── Final_Optimised_structure_test_in_ML.xlsx
    └── Predefined_structure_test.xlsx
```

---

# Main Dataset

### File

```
concatenated_all_final.xlsx
```

This file contains the full dataset used for training machine learning models.

Each row represents a simulated stacked absorber solar cell structure and includes both material parameters and device performance metrics.

---

# Feature Description

The dataset includes parameters for two absorber layers.

## Layer 1 Parameters

| Column       | Description                                        |
| ------------ | -------------------------------------------------- |
| L1 Thickness | Thickness of absorber layer 1                      |
| L1 Bg        | Bandgap energy                                     |
| L1 Ea        | Electron affinity                                  |
| L1 Dp        | Defect density                                     |
| L1 Nc        | Effective density of states in the conduction band |
| L1 Nv        | Effective density of states in the valence band    |
| L1 Ue        | Electron mobility                                  |
| L1 Uh        | Hole mobility                                      |
| L1 Na        | Acceptor concentration                             |
| L1 dd        | Defect distribution parameter                      |

---

## Layer 2 Parameters

| Column       | Description                                        |
| ------------ | -------------------------------------------------- |
| L2 Thickness | Thickness of absorber layer 2                      |
| L2 Bg        | Bandgap energy                                     |
| L2 Ea        | Electron affinity                                  |
| L2 Dp        | Defect density                                     |
| L2 Nc        | Effective density of states in the conduction band |
| L2 Nv        | Effective density of states in the valence band    |
| L2 Ue        | Electron mobility                                  |
| L2 Uh        | Hole mobility                                      |
| L2 Na        | Acceptor concentration                             |
| L2 dd        | Defect distribution parameter                      |

---

# Output Performance Parameters

| Column | Description                   |
| ------ | ----------------------------- |
| Voc    | Open circuit voltage          |
| Jsc    | Short circuit current density |
| FF     | Fill factor                   |
| PCE    | Power conversion efficiency   |

These values represent the simulated photovoltaic performance of each device structure.

---

# Structure Identifier

The dataset contains a **Structure** column which labels each device configuration.

```
Structure_1
Structure_2
...
Structure_24
```

Each label corresponds to a unique combination of absorber materials and BSF layers.

---

# Device Material Combinations

## First Absorber Layer Materials

Six materials were selected for the first absorber layer:

* CuInS₂
* CZTS
* SnSe
* ZTN
* CdTe
* Si

---

## Second Absorber Layer Materials

Four materials were selected for the second absorber layer:

* CuInSe₂
* AgGaTe₂
* CTS
* CIT

---

## Back Surface Field (BSF) Materials

To ensure efficient carrier transport and improved band alignment, a BSF layer was introduced in each device structure.

Candidate BSF materials:

* MoS₂
* WSe₂
* CGS

---

# Device Structure Combinations

The dataset represents **24 unique stacked absorber structures**, obtained from combinations of the first and second absorber layer materials.

```
6 first-layer materials × 4 second-layer materials = 24 structures
```

Each structure corresponds to one configuration labeled in the **Structure column**.

---

# Validation and Testing Dataset

Additional datasets are provided for model evaluation inside the folder:

```
Dataset_For_validating
```

## Files

### Final_Optimised_structure_test_in_ML.xlsx

Contains optimized device structures predicted using machine learning models.
This dataset is used to evaluate the performance of ML-based optimization.

---

### Predefined_structure_test.xlsx

Contains predefined device structures used to test the predictive capability of the trained models.

---

# Dataset Usage

This dataset is intended for:

* Machine learning model training
* Solar cell performance prediction
* Device structure optimization
* Model validation and benchmarking

The dataset is formatted for direct use in common machine learning frameworks such as:

* Python (Pandas, Scikit-learn)
* XGBoost
* Neural Networks
* Deep Learning models

---

# Notes

All data in this dataset originates from numerical simulations of stacked absorber heterostructure solar cells and is organized to facilitate machine learning-based performance prediction.
