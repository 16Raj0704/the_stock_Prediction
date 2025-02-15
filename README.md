# Stock Price Prediction App 📈

This is a **Stock Price Prediction App** built using **Streamlit**. It utilizes machine learning models, including **Linear Regression** and **LSTM**, to predict stock prices. The app also incorporates sentiment analysis from news headlines to enhance prediction accuracy.

---

## Features 🚀

- **One-Day Prediction (Linear Regression)**: Predicts the next trading day's stock price.
- **Long-Term Prediction (LSTM)**: Provides long-term stock price forecasts.
- **Sentiment Analysis**: Analyzes news headlines for sentiment to improve prediction.
- **Technical Indicators**: Uses RSI, Bollinger Bands, Moving Averages, and more.
- **Interactive Visualizations**: Displays historical and predicted stock prices using Plotly.

---

## Tech Stack 🛠️

- **Frontend**: Streamlit
- **Backend**: Python, TensorFlow
- **Machine Learning**: Scikit-learn, LSTM (TensorFlow)
- **Data Sources**: Yahoo Finance (yfinance), NewsAPI
- **Visualization**: Plotly

---

## Installation 📥

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Get your [NewsAPI](https://newsapi.org/) key and update the script with your key.

---

## Usage 🚀

Run the Streamlit app using:
```bash
streamlit run combine.py
pip install -r requirements.txt
.
├── combine.py          # Main app file
├── requirements.txt    # Required packages
└── README.md            # Documentation (This file)
