# Dynamic Market Insights Tool (DMIT) & ForexFactory Web Scraper

This repository provides a Google Colab notebook for running two tools:

- **Dynamic Market Insights Tool (DMIT)**: A Streamlit app that visualizes stock market data and builds an LSTM model for price predictions.
- **ForexFactory Web Scraper**: A tool that scrapes forex calendar data and exports it to a CSV file.

## Getting Started

Follow these steps to run the tools on Google Colab:

### 1. Install Necessary Libraries

Run the following cell to install required libraries and `localtunnel`:

```python
!pip install streamlit yfinance pandas requests numpy matplotlib pandas_datareader keras scikit-learn selenium
!npm install -g localtunnel
'''
