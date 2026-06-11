# Backdoor Detection in ML-based Intrusion Detection Systems
Course: Machine Learning Security; Master Degree in Cybersecurity
University: Università degli Studi di Roma "La Sapienza"

## Project Overview
This project implements and analyzes a backdoor attack on an IDS model trained on the NSL-KDD dataset, followed by a defense mechanism and explainability analysis.
The project is structured in two main phases:
- **Attack phase**: backdoor injection via data poisoning on a Random Forest and DNN classifier
- **Defense phase**: anomaly detection (Isolation Forest) to sanitize the training set, followed by retraining; activation Clustering was also tested but proved ineffective on tabular data

SHAP explainability is used to visualize the backdoor's effect on model predictions.

## Dataset
The project uses the **NSL-KDD** dataset given by the professors.

## Setup
```bash
pip install -r requirements.txt
```

Then run the notebooks in order:
1) start.ipynb
2) attack.ipynb
3) defense.ipynb
4) explainability.ipynb

## Dependencies
See `requirements.txt`.
