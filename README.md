# GameVault Publishing – Acquisition Screener

## Problem
GameVault needs a data‑driven system to identify games with long‑term value vs short‑term buzz, based on user reviews.

## Solution
- **EDA** revealed key signals: recommendation rate, hours played, helpful votes, sentiment trend.
- **Heuristic scoring** (demand, satisfaction, resilience) provides interpretable baseline.
- **ML model** (Logistic Regression on numeric features) predicts acquisition probability per review, achieving ROC AUC = X.XX (fill in your result).
- **Interactive dashboard** (Streamlit) lets users upload any game’s reviews and get an immediate “Acquire / Monitor / Pass” decision.

## How to run
1. Clone repo
2. Install dependencies: `pip install -r dashboard/requirements.txt`
3. Run dashboard: `streamlit run dashboard/app.py`
4. Upload a CSV with the required columns.

## AI Use Declaration
This project used AI assistance as follows:
- ChatGPT: generated initial code for EDA and some feature engineering
- GitHub Copilot: minor autocompletions.
All final analysis and recommendations are my own.

