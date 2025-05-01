# Telco Churn Survival & CLV Analysis

This project applies survival analysis and CLV modeling on a telco customer dataset to identify churn risks and estimate customer value over time.

## 📊 Project Summary

- **Model Used**: LogNormal AFT (Accelerated Failure Time) Model via `lifelines`
- **Goal**: Predict customer churn time, identify high-risk segments, and calculate Customer Lifetime Value (CLV)
- **Best Model**: LogNormal (AIC = 2944.20, Concordance = 0.78)
- **Most Valuable Segments**: Married, older customers on Total/Plus/E-service plans

## 🛠 Features

- AFT model fitting (Weibull, LogNormal, LogLogistic, Exponential)
- Model comparison via AIC and survival curves
- CLV calculation using survival probabilities
- Segment-wise CLV density plots (e.g., region, marital status, internet usage)
- Final report with actionable retention insights

## ⚙️ How to Run

1. Clone the repository or download the project files.
``` 
https://github.com/annaminasyann/Survival_Analysis.git
```

2. Install dependencies using:

```
pip install -r requirements.txt
```

3. Run DS223Anna_MinasyanHW5.ipynb


- Author: Anna Minasyan


