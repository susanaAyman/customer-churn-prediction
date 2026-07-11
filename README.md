# Customer Churn Prediction

End-to-end Customer Churn Prediction using Machine Learning, FastAPI, and Streamlit.

**Status:** 🚧 In Progress (Day 1)

---

## Business Problem

Customer churn is when a customer stops using a company's product or service.
For subscription-based businesses (telecom, SaaS, banking, streaming, etc.),
acquiring a new customer is far more expensive than retaining an existing one.

This project aims to predict **which customers are likely to churn**, so a
business could proactively intervene (e.g. with a retention offer) before
losing them.

## Dataset

[Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
(IBM sample dataset, adapted version on Kaggle) — 7,043 customers, 21 features,
including demographics, account information, and services subscribed to.

## Technologies (planned)

- **Data analysis / modeling:** Python, Pandas, NumPy, scikit-learn, Jupyter
- **Visualization:** Matplotlib, Seaborn
- **Model explainability:** SHAP
- **API:** FastAPI
- **Dashboard:** Streamlit
- **Testing:** Pytest
- **Version control:** Git + GitHub

## Project Structure

```
customer-churn-prediction/
│
├── data/
│   ├── raw/              # original, unmodified data
│   └── processed/        # cleaned/feature-engineered data
│
├── notebooks/             # exploratory analysis (EDA, experiments)
│
├── src/
│   ├── data/               # data loading/cleaning scripts
│   ├── features/           # feature engineering
│   ├── models/              # training/evaluation scripts
│   ├── visualization/    # plotting helpers
│   └── utils/                # shared utility functions
│
├── api/                    # FastAPI app for serving predictions
├── dashboard/          # Streamlit app
├── models/               # saved/trained model artifacts
├── reports/              # generated analysis reports, figures
├── tests/                  # unit tests
│
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

## Setup

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Roadmap

- [x] Day 1: Project setup, repo structure, dataset download, business problem research
- [ ] Day 2: Exploratory Data Analysis (EDA)
- [ ] Day 3: Data cleaning & feature engineering
- [ ] Day 4: Baseline model training & evaluation
- [ ] Day 5: Model tuning & explainability (SHAP)
- [ ] Day 6: FastAPI serving layer
- [ ] Day 7: Streamlit dashboard
- [ ] Day 8: Deployment & documentation polish

## License

See [LICENSE](LICENSE).
