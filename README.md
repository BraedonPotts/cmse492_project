# Stock Price Prediction (CMSE 492 Project)

This project explores building and evaluating machine learning models to predict future stock prices from historical market data (e.g., OHLCV). The goal is not just to get the lowest error, but to build a **reproducible** pipeline: data ingestion → preprocessing → modeling → evaluation → reporting.

## Directory Structure

```text
cmse492_project/
├── README.md              # You are here
├── .gitignore             # Ignore data dumps, venvs, .ipynb_checkpoints, etc.
├── data/
│   ├── raw/               # Original/unmodified data (CSV, API dumps). Do NOT edit by hand.
│   └── processed/         # Cleaned/feature-engineered data ready for modeling
├── notebooks/
│   └── exploratory/       # Jupyter notebooks for EDA, probing features, quick tests
├── src/
│   ├── preprocessing/     # Scripts to load/clean/merge time series data
│   ├── models/            # Training scripts and model definitions (LSTM, RF, baseline)
│   └── evaluation/        # Metrics, backtests, plots
├── figures/               # Saved plots (correlations, predictions vs actual, etc.)
├── docs/                  # Reports / writeups / presentation assets
└── requirements.txt       # Python dependencies
