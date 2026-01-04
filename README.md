# Car Insurance Claims Fraud & Cost Analysis

## Summary

Noursine Amira, Maycem Azaza, Rahma Haddouchi, Lina Brahmi

Car Insurance Claims Fraud & Cost Analysis

1. Industry and Organization Description:
The project operates within the Property & Casualty Insurance sector. This industry focuses on protecting vehicle & liability coverage. It is a data-intensive sector where profitability relies heavily on accurate risk assessment and efficient claims management. This project aims to generate insights from available data to identify weaknesses and diagnose insurance fraud early on.

## Key Findings

- Insurance fraud drains profits through staged accidents, exaggerated injuries, and fake claims, raising premiums for honest customers.
- Manual detection is slow and inconsistent; a significant percentage of claims are suspected to be fraudulent.
- Operational inefficiency: adjusters spend time on low-risk claims while high-value fraudulent claims slip through.
- Lack of centralized visibility into factors like incident severity, demographics, and age correlating with financial losses.

## Project Structure

Project files and folders (top-level):

```
├── Car Insurance Claims Fraud & Cost Analysis.pdf
├── Data/
│   ├── insurance_fraud_data.csv
│   └── insurance_fraud_data_cleaned.csv
├── Data Preparation.ipynb
└── Data Modeling/
	├── MODELISATION.pbix
	├── model_diagram.png
	└── Measure Definitions.xlsx
```

## Notebooks and Data

- `Data Preparation.ipynb`: exploratory analysis and experiments
- `Data/insurance_fraud_data_cleaned.csv`: cleaned dataset ready for modeling
- `Data/insurance_fraud_data.csv`: raw dataset

## Data Modeling

The `Data Modeling/` folder contains the Power BI model, measurements, and a diagram illustrating the model relationships.

Model diagram:

![Model diagram](Data%20Modelling/model_diagram.png)

## How to Use

1. Open the notebook `Data Preparation.ipynb` in Jupyter Lab/Notebook.
2. Install required packages:

```bash
pip install -r requirements.txt  
```

## Requirements

- Python 3.8+
- Jupyter
- pandas, numpy, scikit-learn, matplotlib, seaborn


