# Binance-Data
# Real-Time Cryptocurrency Price Analysis System

## Overview
This project provides a detailed system for analyzing cryptocurrency prices in real-time using Binance’s public API. The system is designed to continuously collect, process, and store cryptocurrency market data, including:

- Current prices  
- 24-hour price changes  
- Highs and lows  
- Trading volumes  

Data is updated every five minutes to ensure accurate tracking of short-term market trends.

## Features
- **Real-Time Data Collection**: Fetches cryptocurrency price data from Binance API every five minutes.  
- **Data Processing & Storage**: Organizes data using `pandas` and saves it in an Excel file with multiple sheets for different market metrics.  
- **Timestamped Entries**: Each record is stored with a UTC timestamp for precise time-based analysis.  
- **Efficient Data Management**: Optimized to handle large datasets while maintaining clarity and accessibility.  
- **Market Trend Analysis**: Enables tracking of price movements, volume changes, and market fluctuations in real-time.  
- **User-Friendly Storage**: Data is stored in Google Drive for easy access and collaboration.  

## Potential Applications
- Short-term investment strategy development  
- Algorithmic trading system support  
- Financial forecasting and research  
- Anomaly detection in cryptocurrency market trends  
- Building advanced financial models  

## Installation
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-username/crypto-analysis.git
   cd crypto-analysis
