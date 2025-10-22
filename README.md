# Credit Risk Analysis

A concise notebook exploring credit default risk prediction using logistic regression.  
Includes data cleaning, feature engineering, exploratory analysis, and scoring on test data.

---

## Dataset

The data used in this exercise comes from the **Give Me Some Credit** dataset on Kaggle:  
👉 https://www.kaggle.com/c/GiveMeSomeCredit  

Please download the following files from Kaggle and place them in a `data/` folder at the project root:
- `cs-training.csv`
- `cs-test.csv`
- `sampleEntry.csv`
- `Data Dictionary.xls`

---

## Project Structure
```
credit-risk-exercise/
├── credit_risk_analysis.ipynb
├── requirements.txt
└── data/                     # <- Place downloaded Kaggle data here
```

---

## Run Instructions

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Open the notebook:
   ```bash
   jupyter notebook credit_risk_analysis.ipynb
   ```

3. Run all cells (cleaning → modeling → scoring).

