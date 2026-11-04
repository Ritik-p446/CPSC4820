# Live Equity Sentiment & Volatility Forecaster

**Live Dashboard URL:** https://equity-forecaster-kzcgdsyfgj3p9yhd4w4vmg.streamlit.app/

## 1. Project Overview & Organizational Question
Portfolio managers and equity analysts often struggle to reconcile quantitative price momentum with rapidly shifting qualitative news sentiment. This interactive web dashboard pulls on-demand market data and live financial news via the Yahoo Finance API (`yfinance`) to answer a central organizational question:

> *"Given live price momentum, qualitative news sentiment, and predicted 5-day volatility, does a target equity currently present an asymmetric risk-reward opportunity relative to its benchmark index?"*

## 2. Repository File Structure
* `app.py` — Main Streamlit dashboard interface, Plotly visualizations, and cognitive layout controls.
* `data_pipeline.py` — On-demand `yfinance` data ingestion, VADER sentiment analysis, and ethical provenance metadata.
* `model_engine.py` — Quantitative risk calculations, 5-day Ridge Regression forecasting, and automated narrative synthesis.
* `requirements.txt` — Python package dependencies required for local execution and cloud deployment.
* `README.md` — Project documentation and learning outcome mapping.

## 3. How to Run Locally
1. Clone this repository and navigate into the project folder
2. Install the required Python dependencies:
   pip install -r requirements.txt
3. Launch the Streamlit application:
   streamlit run app.py


> **Notice!** This dashboard is developed strictly for academic data visualization and statistical modeling purposes. All market data is sourced on-demand via Yahoo Finance. Predictive bands represent statistical confidence intervals and do not constitute financial or investment advice.
