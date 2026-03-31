# 🚗 Technical Assessment — Data Scientist

This repository contains my submission for Data Scientist Technical Assessment.

---

## 📁 Repository Structure

```
repo_name/
├── question_1/
│   └── question_1_report.pdf
│
├── question_2/
│ ├── accident_classifier.ipynb
│ ├── accident_best_model.pth
│ ├── test_predictions.csv
│ └── question_2_report.pdf
```

---

## 🧠 Question 1 — Problem Framing

This section contains a conceptual proposal for an AI-powered solution to improve operations.

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
| accident_classifier.ipynb | Full implementation (data prep, training, evaluation) |
| accident_best_model.pth | Trained model weights |
| test_predictions.csv | Model predictions on test dataset |
| question_2_report.pdf | Explanation of approach, decisions and deployment plan |

---

## 📈 Predictions Format

The CSV file includes:
- image_filename
- true_label (Accident / Non-Accident)
- predicted_label (Accident / Non-Accident)
- confidence_score

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
