# Stock_price_analysis
An interactive and user-friendly dashboard built using Streamlit to analyze historical stock prices. This project allows users to visualize trends, patterns, and perform basic technical analysis for selected stocks using data from sources like Yahoo Finance.
# 📈 Stock and Price Analysis Dashboard

An interactive **Stock Price Analysis Dashboard** built using **Streamlit** to explore and visualize historical stock performance. This tool allows users to examine market trends, perform basic technical analysis, and visualize data with interactive plots — all within a clean and responsive web interface.

---

## 🚀 Live Access

- **Local URL**: [http://localhost:8501](http://localhost:8501)
- **Network URL**: [http://172.27.194.146:8501](http://172.27.194.146:8501) *(accessible within your local network)*

---

## 🔍 Features

- 📉 Fetch real-time & historical stock data via `yfinance`
- 📊 Line charts for **Open**, **Close**, **High**, **Low** prices
- 📆 Custom date range selection
- 🟢 Moving Averages (SMA, EMA)
- 🕯️ Candlestick Charts using Plotly
- 📥 Export stock data to CSV
- 🧠 Easy-to-use sidebar filters for interactivity

---

## 🛠️ Built With

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [yfinance](https://pypi.org/project/yfinance/)
- [Plotly](https://plotly.com/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/) *(optional)*

---


# Launch the Streamlit app
streamlit run app.py
stock-price-analysis/
│
├── app.py                 # Main Streamlit dashboard
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── data/                  # Optional static or sample data
