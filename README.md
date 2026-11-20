# Bank Term Deposit Subscription Classification

Telemarketing campaign response prediction model identifying clients likely to subscribe to a bank term deposit.

## Project Structure

```text
03_Bank_Deposit_Classification/
├── bank_deposit_classification_data.csv
├── bank_deposit_classification_pipeline.ipynb
├── app.py
├── best_model.pkl
├── model_metadata.json
├── requirements.txt
└── README.md
```

## Dataset & Features

- **Dataset File:** `bank_deposit_classification_data.csv`
- **Task Type:** `Classification`
- **Target Variable:** `deposit_subscribed`
- **Numerical Features (4):** `age, balance, duration, campaign`
- **Categorical Features (7):** `job, marital, education, housing, loan, contact, poutcome`

## Model Evaluation Summary

- **Selected Best Model:** `LogisticRegression`

| Metric | Score |
| :--- | :--- |
| `accuracy` | `0.9667` |
| `f1_score` | `0.9474` |
| `roc_auc` | `0.9887` |

## Quickstart & Deployment

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Streamlit web application:
   ```bash
   streamlit run app.py
   ```
