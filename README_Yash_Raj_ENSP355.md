# Mini AI Cybersecurity Assistant

**Student:** Yash Raj  
**Roll Number:** 2401010008  
**University:** K.R. Mangalam University  
**Programme:** B.Tech CSE (Core)  
**Course:** ENSP355 – AI in Cyber Security

## Project Overview

This Google Colab notebook implements a small AI-assisted cybersecurity prototype. It analyzes a sample message and login-activity information to identify possible cyber threats and produce a risk-aware recommendation.

The notebook combines:
- Rule-based checks for phishing, malware, and ransomware indicators.
- A Decision Tree model to classify login activity as Normal or Suspicious.
- A small neural network to estimate whether login activity is suspicious.
- Explanations of detected keywords and model results.
- Privacy masking for sensitive identifiers.
- Risk levels, recommended actions, and human-review controls.

## Files

- `Yash_Raj_ENSP355_AI_Cybersecurity_Assistant.ipynb` — main Google Colab notebook.
- The notebook creates the sample message and login datasets as CSV files when its relevant cells are run.

## How to Run in Google Colab

1. Download the `.ipynb` notebook.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File → Upload notebook** and upload the notebook.
4. In the notebook, select **Runtime → Run all**.
5. Wait for all cells to finish and review the displayed tables, metrics, charts, and scenario results.
6. Download any generated CSV outputs if they are required for submission.

## Dataset and Safety

This is an educational prototype using synthetic/sanitized sample data. Do not enter real passwords, personal information, institutional confidential data, or live account details. Do not open suspicious links, execute malware, scan networks, or test live accounts.

Model outputs are decision-support signals only. High-risk, conflicting, or low-confidence results should be checked by an authorized human reviewer.

## Notes

- Run all notebook cells in order.
- If a cell reports an error, check that the previous setup and data cells have run successfully.
- The notebook should be reviewed and understood by the student before submission.
