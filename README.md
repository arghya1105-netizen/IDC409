# Finance + News: Next-Day Stock Movement Prediction

## Goal
Collect share, gold, oil and currency data plus news headlines, and test
whether news keywords help predict next-day stock direction.

## Data sources
- Prices: yfinance (RELIANCE.NS, GC=F, CL=F, USDINR=X)
- News: Google News RSS / NewsAPI
- Limitations: oil futures used as a petrol proxy; news history is short

## How to run
1. Open the notebooks in `notebooks/` in Google Colab, in order:
   - 01_data_collection.ipynb
   - 02_eda.ipynb
   - 03_model.ipynb
2. Install requirements: `pip install -r requirements.txt`
