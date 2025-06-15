# Bitcoin_Price_Estimation
# 🪙 Bitcoin Price Estimation & Sentiment Analysis

This project is a **Streamlit-based web app** that integrates machine learning and deep learning models to predict **Bitcoin prices** and analyze **market sentiment** based on news headlines. It combines time series forecasting (LSTM) with natural language processing (Random Forest + TF-IDF) to provide a data-driven insight into the crypto market.

---

## 🚀 Features

- 📈 **LSTM-based Time Series Forecasting** of Bitcoin prices using historical data
- 💬 **Sentiment Analysis** on news headlines using TF-IDF and Random Forest
- 📊 Interactive Streamlit UI for real-time predictions and visualizations
- 🧠 Model files stored for reproducibility: `.pkl` and `.h5`

---

## 📁 Project Structure

Bitcoin_Price_Estimation/
│
├── app.py                     # Streamlit app
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
│
├── models/                    # Pretrained models
│   ├── rf_model.pkl           # Random Forest classifier
│   ├── tfidf_vectorizer.pkl   # TF-IDF vectorizer
│   └── btc_lstm_model.h5      # LSTM model for price prediction

## 🛠️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/ZainabNaveed13/Bitcoin_Price_Estimation.git
   cd Bitcoin_Price_Estimation

   ## 🔧 Install Dependencies


pip install -r requirements.txt
