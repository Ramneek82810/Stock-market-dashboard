# 📊 Stock-Market Dashboard
 
An interactive and real-time stock market dashboard built using Python and data visualization tools. This project helps users track and analyze stock performance, visualize trends, and make informed decisions with ease.

## 🚀 Features
 
- 📈 Real-time stock price tracking   
- 📊 Interactive charts for historical stock data   
- 🔍 Search and filter functionality for specific stocks  
- 📅 Date range selectors for time-based analysis   
- 💡 Clean and intuitive user interface    
   
## 📁 Project Structure 
 
```
Stock-market-dashboard/
│
├── stock_market_dashboard.ipynb      # Main dashboard script
└── README.md               # You're reading it!
```

## ⚙️ Installation

### 1. Clone the Repository

```
git clone https://github.com/Ramneek82810/Stock-market-dashboard.git
cd Stock-market-dashboard
```

### 2. Create and Activate Virtual Environment (optional but recommended)

```
python -m venv .venv
source .venv/bin/activate    # On Windows use: .venv\Scripts\activate
```

### 3. Install Dependencies

```
pip install streamlit yfinance pandas matplotlib plotly
```

## 🧪 Run the Dashboard

```
streamlit run dashboard.py
```

This will open the stock dashboard in your browser at `http://localhost:8501`

## 💡 How It Works

- Uses `yfinance` to fetch real-time and historical stock data  
- Visualizes data using `plotly` and `matplotlib`  
- Powered by `Streamlit` for fast, interactive UI development  
- Filters and plots can be adjusted in real-time based on user input  

## 📌 Todo 

- Add sector-wise stock filters  
- Implement portfolio simulation  
- Include news sentiment analysis  
- Add export/download report functionality  

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.
