# DermAI Dataset 
## Overview

This repository contains the **dataset engineering phase** of the DermAI project.
It represents the first stage of the AI development pipeline, focusing on preparing a clean, validated, and well-structured dataset for downstream machine learning and deep learning tasks in skin lesion classification.

The work in this repository establishes a reliable data foundation to ensure model stability, fairness, and reproducibility.

---

## Objectives

* Acquire and organize dermoscopic image datasets
* Perform data cleaning and quality validation
* Analyze class distribution and dataset imbalance
* Apply standardized preprocessing techniques
* Document exploratory data analysis and dataset decisions

---

## Dataset Description

The dataset consists of labeled dermoscopic images of skin lesions collected from publicly available sources such as ISIC.

> **Note:** Due to licensing restrictions, raw image data is not included in this repository.
> This repository contains only the code, notebooks, and scripts used to process and analyze the dataset.

---

## Repository Structure

```
DermAI_Dataset/
├── notebooks/
│   └── DermAI_Dataset.ipynb
│
├── src/
│   ├── cleaning.py
│   ├── preprocessing.py
│   └── validation.py
│
├── outputs/
│   ├── class_distribution/
│   └── sample_visualizations/
│
└── README.md
```

---

## Methodology

### 1. Data Cleaning

* Removal of corrupted or unreadable images
* Validation of image-label consistency
* Standardization of file naming and directory structure

### 2. Dataset Validation

* Verification of class labels
* Detection of duplicates
* Class distribution analysis to identify imbalance

### 3. Preprocessing

* Image resizing and normalization
* Preparation of data generators for training
* Consistent preprocessing pipeline for all downstream models

---

## Notebooks vs Scripts

* **Jupyter Notebook (`.ipynb`)**
  Used for exploratory data analysis, visualization, and documentation of dataset decisions.

* **Python Scripts (`.py`)**
  Used for reusable, clean, and reproducible preprocessing and validation pipelines.

This separation ensures clarity between experimentation and production-level code.

---

## Outputs

Generated outputs include:

* Class distribution plots
* Sample visualizations before and after preprocessing
* Validation summaries

All outputs are stored in the `outputs/` directory.

---






احكيلي 👍
