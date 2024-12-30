# Stock Price Prediction with LSTM Model

This project demonstrates how to download historical stock data, preprocess it, train a Long Short-Term Memory (LSTM) model for stock price prediction, and upload the data to Google BigQuery for storage and further analysis. The model is based on Apple's stock (AAPL), but it can be adapted for other stocks as well.

## Prerequisites

Before you run the script, ensure you have the following installed:

- Python 3.x
- Google Cloud SDK (for BigQuery)
- Required Python Libraries (see below for installation)

## Setup Instructions

### 1. Install Required Libraries

The script requires several Python libraries, which you can install using `pip`. Here's the list of required packages:

```bash
pip install google-cloud-bigquery google-auth yfinance stockstats pandas numpy tensorflow matplotlib scikit-learn plotly pyarrow pandas-gbq
