# Healthcare Admission Forecasting — Synthetic Demo

## Project overview
A portfolio demonstration of monthly admission forecasting across six fictional channels using Python.

**All data, forecasts, metrics, and charts in this repository are synthetic and fictional.** No real hospital records, patient information, or confidential organizational data are included.

## Channels
Cash, CGHS, Corporate, EWS, International, TPA.

## Models
- **ETS (Exponential Smoothing):** additive trend, damped trend, and additive yearly seasonality.
- **Recent Average:** average of the latest four complete monthly totals.

The notebook performs monthly walk-forward evaluation for January–October 2026, calculates MAE, RMSE, MAPE, WAPE, and bias, selects a model per channel based on WAPE, and forecasts November–December 2026.

## Visualizations
1. Actual vs Predicted — Monthly (2026)
2. Channel-wise Actual vs Predicted (2026)

Both charts display numeric values.

## Run
Open `Admission_Forecasting.ipynb` in Google Colab or Jupyter and run the cells. The notebook reads `sample_data/synthetic_admission_data.xlsx` and writes an illustrative report to `outputs/`.

## Repository structure
- `Admission_Forecasting.ipynb` — complete forecasting notebook
- `sample_data/` — synthetic Excel dataset
- `outputs/` — generated synthetic report
- `requirements.txt` — Python dependencies

## Data privacy
Only synthetic data is included. Do not replace it with confidential, proprietary, or patient-identifiable data when publishing.

## Disclaimer
This is an educational portfolio project. Synthetic results are illustrative and do not represent any real hospital's operations or forecasting performance.
