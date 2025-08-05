# Stock-sentiment-prediction
Financial Market Sentiment Analysis and Price Prediction Project

## Overview
This project predicts short-term stock price movements by combining historical stock price data with sentiment analysis of financial news and social media. It also generates AI-powered daily market summaries and trading insights.

## Features
- Fetches historical stock prices using Yahoo Finance API
- Collects financial news headlines via NewsAPI
- Performs sentiment analysis on news headlines and social media text
- Builds machine learning models to predict stock price direction
- Generates natural language market summaries using AI (OpenAI GPT)
- Displays data, predictions, and AI insights in an interactive dashboard (Streamlit)

## Getting Started

### Prerequisites
- Python 3.8 or higher installed on your computer
- API keys for:
  - [NewsAPI](https://newsapi.org/) (to fetch financial news)
  - [OpenAI](https://openai.com/api) (to generate AI summaries)
- Basic Python libraries installed (listed in `requirements.txt`)

### Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/VenkatAmit/stock-sentiment-prediction.git
  
   
2. Navigate to the project folder:
   ```bash
   cd stock-sentiment-prediction

3. Create and activate a Python virtual environment:
   ```bash
   python3 -m venv myenv
   source myenv/bin/activate

4. Install the required packages:
   ```bash
   pip install -r requirements.txt

## Usage

1. Make sure your virtual environment is activated:
   ```bash
   source myenv/bin/activate

2. Fetch stock price data and news headlines by running:
   ```bash
   python scripts/data_fetch.py

3. Perform sentiment analysis on the collected news:
   ```bash
   python scripts/sentiment_analysis.py

4. Train the stock price prediction model:
   ```bash
   python scripts/train_model.py

5. Generate AI-powered market summaries:
   ```bash
   python scripts/generate_insights.py

6. Launch the interactive dashboard:
   ```bash
   streamlit run dashboard.py

## Project Structure

```plaintext
stock-sentiment-prediction/
├── data/                  # Raw and processed data files
├── notebooks/             # Jupyter/Colab notebooks or VS Code scripts for exploration and experiments
├── scripts/               # Python scripts for data collection, analysis, and modeling
├── dashboard.py           # Streamlit app for visualization and user interaction
├── requirements.txt       # List of Python dependencies
└── README.md              # Project overview and instructions
