# DriveSafe-AI: FMCSA Compliance Auditor

## Overview
This project uses Natural Language Processing (NLP) to automatically detect compliance violations in trucking log entries. The goal is to reduce manual review time and improve accuracy in identifying safety issues.

## Problem
Trucking companies must follow strict FMCSA regulations, including Hours of Service (HOS) rules. Reviewing driver logs manually is time-consuming and can lead to human error.

## Solution
I built a text classification system using a Transformer-based model (DistilBERT) to categorize log entries into:
- SAFE
- HOS_VIOLATION
- FORM_ERROR
- MISSING_DATA
- INSPECTION_ISSUE

## Technologies Used
- Python
- Transformers (DistilBERT)
- NLP techniques
- Jupyter Notebook

## Results
- Accuracy: 94%
- F1 Score: 0.94

The model performs well in detecting violations and can support faster and more reliable compliance checks.

## Example
Input:
"Driver exceeded maximum driving hours without required rest"

Output:
HOS_VIOLATION

## Business Impact
This system can help trucking companies:
- Reduce manual audit time
- Detect violations faster
- Improve safety compliance
- Avoid FMCSA penalties

## Future Improvements
- Use real-world ELD data
- Expand dataset size
- Build a web interface for easier use

## Files
- `main.py` — core model / logic
- `analysis.ipynb` — experimentation and training
- `project_report.pdf` — detailed report
