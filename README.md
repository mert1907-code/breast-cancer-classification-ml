# AI-Powered Breast Cancer Diagnosis System 🔬

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-green)

This repository contains the final deliverables for the Machine Learning Classification Project. The project develops a highly sensitive Clinical Decision Support System (CDSS) for classifying breast cancer tumors (Malignant vs. Benign) using both traditional machine learning ensembles and an innovative deep learning approach.

## 📖 Project Overview
Breast cancer diagnosis relies heavily on the histological evaluation of biopsied cell nuclei. The critical challenge in this domain is minimizing the **False Negative Rate (FNR)**. 

This project explores a dual-paradigm framework:
1. **Tabular Machine Learning:** Establishing robust baselines using Logistic Regression, SVM, and Random Forest models.
2. **Spatial Deep Learning (GAF-CNN):** Transforming 1D clinical tabular data into 2D structural images via the **Gramian Angular Field (GAF)** method, followed by feature extraction using Convolutional Neural Networks (CNN).

## 📊 Dataset
The models are trained and evaluated on the standard **Wisconsin Breast Cancer (Diagnostic) Dataset**.
* **Instances:** 569 patient records
* **Features:** 30 continuous numerical clinical parameters (radius, texture, perimeter, area, smoothness, etc.)
* **Target:** `diagnosis` (M = Malignant, B = Benign)

## ⚙️ Installation & Setup (How to Reproduce)
To run this project locally and reproduce the results, please follow the instructions below:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git)
   cd YOUR_REPOSITORY_NAME
