# DriveSafe AI: FMCSA Compliance Auditor

## Overview
DriveSafe AI is a Natural Language Processing (NLP) project that automatically detects compliance violations in trucking log entries. The goal is to reduce manual review time and improve accuracy in identifying safety issues.

---

## Problem
Trucking companies must comply with FMCSA regulations, including Hours of Service (HOS) rules. Manual log review is time-consuming, repetitive, and prone to human error.

---

## Solution
I built a text classification system using a Transformer-based model (DistilBERT) to analyze trucking log entries and classify them into compliance categories.

### Classes:
- SAFE  
- HOS_VIOLATION  
- FORM_ERROR  
- MISSING_DATA  
- INSPECTION_ISSUE  

---

## Approach

The project follows a standard NLP pipeline:

1. Data preprocessing and cleaning  
2. Tokenization using DistilBERT tokenizer  
3. Model training using supervised learning  
4. Evaluation using accuracy and F1-score  

---

## Technologies Used

- Python  
- Hugging Face Transformers (DistilBERT)  
- PyTorch  
- Scikit-learn  
- Pandas  
- Jupyter Notebook  

---

## Results

- Accuracy: **94%**  
- Weighted F1-score: **0.94**  

The model performs well in identifying different types of compliance violations and can support faster log review.

---

## Example

**Input:**  
"Driver exceeded maximum driving hours without required rest"

**Output:**  
HOS_VIOLATION  

---

## Business Impact

This system can help trucking companies:
- Reduce manual audit time  
- Detect violations faster  
- Improve safety compliance  
- Minimize risk of FMCSA penalties  

---

## Future Improvements

- Train on real-world ELD data  
- Expand dataset size  
- Build a web-based interface for real-time use  
