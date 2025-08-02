# Predicting Price Moves with News Sentiment

This project predicts stock price movements by analyzing news sentiment. It uses TextBlob for sentiment scoring and examines correlations between news sentiment and subsequent price changes.

## Workflow
1. **Load Data:** Import raw CSVs from `data/` (e.g. analyst settings and historical stock prices).
2. **Compute Sentiment:** Run sentiment analysis on news headlines/text.
3. **Generate Features:** Compute technical indicators or derived features from price data.
4. **Correlation Analysis:** Compare sentiment metrics with price movements and export correlation tables to `results/`.

## Installation
- Ensure **Python 3.12.6 or  more ** is used (via pyenv, conda, etc.).
- Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```