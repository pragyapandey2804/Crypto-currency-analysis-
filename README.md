# Crypto-currency-analysis-
Sure! Here's a basic and small README for your project:

---

# Cryptocurrency Data Analysis

## Description
This project fetches real-time data for the top 50 cryptocurrencies by market capitalization using the CoinGecko API. The data includes the current price, market capitalization, 24-hour trading volume, and 24-hour price change. It analyzes this data to identify key trends and updates an Excel sheet every 5 minutes.

## Features
- Fetches live cryptocurrency data for the top 50 cryptocurrencies.
- Displays the top 5 cryptocurrencies by market cap.
- Calculates the average price of the top 50 cryptocurrencies.
- Analyzes the highest and lowest 24-hour price changes.
- Continuously updates the data in a CSV file every 5 minutes.

## Requirements
- Python 3.x
- `pandas` library
- `pycoingecko` library

## Setup
1. Install the required libraries:
   ```bash
   pip install pandas pycoingecko
   ```

2. Run the Python script to start fetching data:
   ```bash
   python crypto_analysis.py
   ```

3. The data will be saved in a CSV file called `crypto_analysis.csv` and will update every 5 minutes.

---

This README provides a basic overview of the project and how to set it up.
