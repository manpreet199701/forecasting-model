# Forecasting Model
**One-line pitch:** Small time-series forecasting demo (finance) using Python + AWS.

**Skills:** Python, pandas, scikit-learn, AWS (S3, SageMaker), Jupyter

---

## Demo
(put `demo/demo.gif` here or link a short video)

## Problem
Predict next-period value (stock/sales) to help planning/decisions.

## Data
- Source: sample CSV in `data/` (small subset included)
- Notes: sample data only; link to full dataset in README

## Approach
1. Load & clean (`notebooks/01-python-basics.ipynb`)
2. Build baseline model (ARIMA / LinearRegression)
3. (Optional) Train on SageMaker and deploy endpoint

## How to run (local)
1. `python -m venv venv`
2. `source venv/bin/activate`  # Windows: `venv\Scripts\activate`
3. `pip install -r requirements.txt`
4. `jupyter notebook notebooks/01-python-basics.ipynb`

## AWS services used (if deployed)
S3 (data), SageMaker (train + endpoint), Lambda + API Gateway (API)

## Contact
Your Name — Delhi, India  
Portfolio: https://your-portfolio-url  
Email: you@example.com
