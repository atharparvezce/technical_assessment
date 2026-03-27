# 🚗 KFCA Technical Assessment — Data Scientist

This repository contains my submission for the King Fahd Causeway Authority (KFCA) Data Scientist Technical Assessment.

---

## 📁 Repository Structure

```
repo_name/
├── question_1/
│   └── solution.pdf
│
├── question_2/
│   ├── notebook.ipynb
│   ├── model.pth
│   ├── test_predictions.csv
│   └── report.pdf
```

---

## 🧠 Question 1 — Problem Framing

This section contains a conceptual proposal for an AI-powered solution to improve KFCA operations.

### 📄 Contents:
- question1_report.pdf  
  Covers:
  - Problem definition  
  - Data requirements  
  - Proposed AI approach  
  - Success metrics  
  - Conclusion

---

## 🤖 Question 2 — Accident Detection Model

### 🎯 Objective
Build a binary image classification model to predict whether a CCTV frame contains:
- Accident
- Non-Accident

---

## 📊 Files Explained

| File | Description |
|------|-------------|
| notebook.ipynb | Full implementation (data prep, training, evaluation) |
| model.pth | Trained model weights |
| test_predictions.csv | Model predictions on test dataset |
| report.pdf | Explanation of approach, decisions and deployment plan |

---

## 📈 Predictions Format

The CSV file includes:
- image_filename
- true_label (Accident / Non-Accident)
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

Thank you for reviewing my submission. I appreciate your time and consideration.
