# Efficient-EEG-Signal Classifier

An efficient machine learning framework for classifying **mental states** such as **Focusness** and **Drowsiness** using EEG signals collected from real-life neurosignal experiments.  

---

## 🚀 Project Overview
This project aims to build a **lightweight, accurate, and efficient EEG classification pipeline** that can run on real-world, resource-constrained environments (e.g., laptops or embedded systems).  

Key objectives:
- Detect **drowsiness** and **focus levels** from EEG signals.
- Use **efficient preprocessing** methods like FFT (Fast Fourier Transform) to extract frequency-domain features.
- Experiment with multiple **machine learning models** and optimize hyperparameters for the best performance.

---

## 🔬 Methodology

### 1. Preprocessing
- **Noise removal**: Band-pass & notch filters.
- **Artifact handling**: Mitigation of eye-blink and muscle artifacts.
- **Feature extraction**: FFT-based Power Spectral Density (PSD), band power in δ, θ, α, β, γ ranges.

### 2. Feature Engineering
- Band ratios (e.g., θ/α, β/α).
- Engagement and drowsiness indices.
- Normalization for inter-subject variability.

### 3. Machine Learning Models
- **Classical ML**: Logistic Regression, SVM (linear & RBF), Random Forests.

### 4. Evaluation
- Accuracy, Precision, Recall, F1-score (per class).
- ROC-AUC (macro + per-class).
- Confusion matrices.
- Cross-subject validation for generalization.

---

## 📊 Expected Outcomes
- **Accurate drowsiness detection** using minimal compute resources.
- A **survey of ML models and hyperparameters** tailored for EEG-based classification.
- A reproducible pipeline for **future EEG experiments**.
