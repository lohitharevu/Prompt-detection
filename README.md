# Malicious Prompt Detection

## Overview
This project focuses on detecting whether a given prompt is **malicious** or **benign**.

Malicious prompts are inputs that try to manipulate or misuse AI systems. This model helps in identifying such harmful inputs.

---

## Objective
To build a machine learning model that classifies prompts into:
- 0 → Benign  
- 1 → Malicious  

---

## Dataset
- Used the **MPDD dataset**
- Contains labeled prompts (malicious and benign)

---

## Approach

### 1. Data Preprocessing
- Converted text to lowercase  
- Removed special characters  
- Removed stopwords  

---

### 2. Feature Engineering
- **TF-IDF (Word level)** → captures important words  
- **TF-IDF (Character level)** → detects tricky or modified text  
- **Statistical features**:
  - Text length  
  - Word count  
  - Digit count  
  - Uppercase letters  

- **Keyword detection** (e.g., hack, bypass, delete)

---

### 3. Models Used
- Logistic Regression  
- Support Vector Machine (SVM)  

---

### 4. Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

---

## Files in this Project

- `notebook.ipynb` → Full implementation  
- `submission.csv` → Final predictions  
- `final_model.pkl` → Saved model  

---

## How to Run

1. Install required libraries
2. Open the notebook
3. Run all cells

---

## Conclusion
This project builds a reliable model to detect malicious prompts using machine learning and feature engineering techniques.

---

## Author
Lohitha
