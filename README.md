# ds_Samartha
My python developer task for Primetrade.ai - Binance Simplified Trading Bot.

![Python](https://img.shields.io/badge/python-3.9-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

# PrimeTrade.AI - Simplified Binance Futures Trading Bot (Simulated)

This project simulates a Binance Futures Trading Bot for PrimeTrade.ai using a Mock API (since the Binance Futures Testnet is blocked in some regions like India).

## Features
- Place MARKET, LIMIT, and STOP-LIMIT orders
- Support for BUY and SELL sides
- Command-line interaction via Colab
- Logs orders to CSV (`csv_files/order_logs.csv`)
- Written in Python using OOP
- Fully modular and ready to swap with real Binance API

## Folder Structure

```bash 
ds_Samartha/
├── notebook_1.ipynb           # All working code is inside colab notebook
├── csv_files/                 # All CSVs or data outputs are stored here.
│ └── *.csv                    
├── outputs/                   # All visual outputs, graphs, or charts are here.
│ └── *.png / *.jpg            # Image results of EDA, charts, etc.
├── ds_report.pdf              # Final summarized insights and explanations.
└── README.md 
```

## How to Run
1. Open the shared Colab notebook link
2. Enter inputs when prompted
3. Orders will be simulated and logged

## Technologies Used
- Python
- Google Colab
- python-binance
- Pandas, Logging

## Notes
 This bot is API-compatible. Replace `MockBinanceClient` with `Client` from `python-binance` for real trading.
"""
with open("README.md", "w") as f:
    f.write(readme_text)
print("README.md generated.")


## Author

**Samartha**  
B.Tech student 
🎓 AI/ML • Data Science •  NLP • Google Cloud 
🔗 [LinkedIn](https://www.linkedin.com/in/samartha-b0154a293) | [GitHub](https://github.com/Samartha21BRS1698)

📝 License
 MIT License © 2025 Samartha
