# 🧠 WiDS Datathon 2025 – Multimodal Brain Imaging Prediction

## 📌 Overview
This repository contains the Python implementation for the **WiDS (Women in Data Science) Datathon 2025** challenge.  
The goal of this project was to predict clinical or cognitive outcomes using **multimodal data**—including **quantitative features, categorical metadata, and brain functional connectome matrices**.

---

## 🎯 Objectives
- Preprocess and integrate multiple data modalities (quantitative, categorical, imaging).
- Handle missing values, scaling, and feature dimensionality reduction.
- Build and validate machine learning models to predict the target variable with high accuracy.
- Evaluate models using F1 score and Brier score metrics.

---

## 🧩 Project Structure

- **WIDS_Final.ipynb** — Main notebook containing the complete machine learning pipeline  
  - **Data Loading** – Reads Excel and CSV files from Google Drive  
  - **Data Merging** – Combines quantitative, categorical, and imaging datasets  
  - **Preprocessing** – Handles missing values, encoding, and feature scaling  
  - **PCA Dimensionality Reduction** – Reduces feature dimensions while retaining 90% variance  
  - **Model Training (XGBoost)** – Trains classifier using optimized hyperparameters  
  - **Cross Validation (Repeated Stratified K-Fold)** – Ensures model generalization and stability  
  - **Evaluation (F1 Score, Brier Score)** – Measures model accuracy and calibration  
  - **Submission Generation** – Produces final prediction file in required format


---

## ⚙️ Key Features
- **Dynamic Data Loading** with error handling and path validation.
- **Feature Engineering & Integration** of multimodal datasets.
- **Principal Component Analysis (PCA)** for high-dimensional imaging data.
- **XGBoost Classifier** optimized using **early stopping**.
- **Cross-validation** using Repeated Stratified K-Fold to ensure generalization.
- **Performance Metrics:** F1-score, Brier score, and confusion matrix visualizations.

---

## 🧰 Tech Stack
- **Python 3**
- **Pandas, NumPy, Matplotlib, Seaborn**
- **Scikit-learn**
- **XGBoost**
- **Google Colab (for Drive integration)**

---

## 🚀 How to Run
1. Clone the repository or upload the notebook to Google Colab.
2. Mount your Google Drive and ensure all dataset files are located in:

3. Run all cells in order to:
- Load and preprocess data  
- Train models  
- Generate submission predictions

---

## 📈 Results Summary
- **Model Used:** XGBoost Classifier  
- **Dimensionality Reduction:** PCA (retaining 90% variance)
- **Evaluation Metrics:**
- F1 Score: ~0.79 (cross-validated)
- Brier Score: ~0.21
- **Outcome:** Successfully generated predictions for the final submission file.

---

## 🏅 Contributors
- **Participant:** Bhoomika Malagar
- **Participant:** Amogh Pai
- **Participant:** Saanvi Shetty
- **Participant:** Shreyas Kulkarni

(WiDS Datathon 2025 Participant – KLE Technological University)

