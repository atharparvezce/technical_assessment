# 🚗 KFCA Technical Assessment — Data Scientist

This repository contains my submission for the King Fahd Causeway Authority (KFCA) Data Scientist Technical Assessment.

---

## 📁 Repository Structure

.
├── question_1/
│   └── solution.pdf
│
├── question_2/
│   ├── notebook.ipynb
│   ├── model.pth
│   ├── test_predictions.csv
│   └── report.pdf

---

## 🧠 Question 1 — Problem Framing

This section contains a conceptual proposal for an AI-powered solution to improve KFCA operations.

### 📄 Contents:
- solution.pdf  
  Covers:
  - Problem definition  
  - Data requirements  
  - Proposed AI approach  
  - Success metrics  

---

## 🤖 Question 2 — Accident Detection Model

### 🎯 Objective
Build a binary image classification model to predict whether a CCTV frame contains:
- Accident
- Non-Accident

---

## ⚙️ Approach Summary

### 1. Data Preprocessing
- Image resizing and normalization  
- Train/test split provided  
- Data augmentation applied (if used)

### 2. Model
- Deep learning-based image classifier (e.g., CNN / Transfer Learning)
- Framework: PyTorch

### 3. Training
- Loss function: Binary Cross-Entropy  
- Optimizer: Adam (or similar)  
- Evaluation on validation/test data  

### 4. Output
- Predictions generated for test set  
- Confidence scores included  

---

## 📊 Files Explained

| File | Description |
|------|-------------|
| notebook.ipynb | Full implementation (data prep, training, evaluation) |
| model.pth | Trained model weights |
| test_predictions.csv | Model predictions on test dataset |
| report.pdf | Explanation of approach, decisions, and deployment plan |

---

## 📈 Predictions Format

The CSV file includes:
- image_filename
- predicted_label (Accident / Non-Accident)
- confidence_score

---

## 🚀 How to Run

1. Clone the repository:
git clone <your-repo-link>
cd <repo-name>

2. Install dependencies:
pip install -r requirements.txt

3. Run the notebook:
jupyter notebook question_2/notebook.ipynb

---

## ☁️ Deployment (Concept)

As described in the report:
- Model can be deployed on Google Cloud Platform (GCP) using:
  - Vertex AI / AI Platform  
  - Cloud Run (for inference API)  
  - Cloud Storage (for data pipeline)

---

## 📌 Notes

- Code is written to be clean, modular, and reproducible
- Model can be further improved with:
  - More data
  - Hyperparameter tuning
  - Advanced architectures

---

## 🙏 Acknowledgment

Thank you for the opportunity to complete this assessment. I appreciate your time and consideration.
