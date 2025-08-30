#📊 Trade Activity & Market Sentiment Analysis


## 🌟 Project Overview

This project explores how market sentiment (Fear, Greed, Neutral, Extreme Greed, and Unknown) affects trading activity over time.
By combining historical trade data with the Fear & Greed Index, we visualize patterns of trader behavior under different emotional conditions.

## 📌 Key Findings:

Traders are most active during Fear sentiment (~135k trades).

Greed sentiment shows steady but moderate activity.

Extreme Greed and Neutral contribute the least.

## 📂 Folder Structure
ds_kanisha_sharma/
├── notebook_1.ipynb           # Colab notebook with full analysis
├── csv_files/
│   ├── fear_greed_index.csv
│   ├── historical_data.csv
│   ├── merged_trades_with_sentiment.csv
│   └── sentiment_summary.csv
├── outputs/
│   ├── daily_trades_over_time.png
│   ├── trades_by_sentiment.png
├── ds_report.pdf              # Final written summary report
└── README.md                  # You are here 🚀

## 📊 Visualizations
1️⃣ Number of Trades by Sentiment

2️⃣ Daily Trade Volume Over Time (by Sentiment)

## 🛠️ Tech Stack

Python 3.11

Pandas – Data wrangling & merging

Matplotlib / Seaborn – Visualizations

Google Colab / Jupyter Notebook – Analysis environment

## 🚀 How to Run

Clone the repository:

git clone https://github.com/yourusername/ds_kanisha_sharma.git
cd ds_kanisha_sharma


Open the notebook in Google Colab or Jupyter:

notebook_1.ipynb

Run all cells to reproduce the analysis.

Outputs will be saved in the /outputs folder automatically.

## 📑 Report

For detailed explanations, insights, and conclusions, check the 📄 ds_report.pdf
.

## 📌 Insights Recap

Fear sentiment drives the highest trading activity → traders respond strongly to uncertainty.

Greed sentiment results in steady but lower trading volume.

Extreme Greed and Neutral periods see minimal activity.

## 💡 Future Improvements

Include PnL and leverage data (if available) to analyze risk/reward behavior.

Add rolling averages and smoothing for long-term sentiment effects.

Build a dashboard (Streamlit/Plotly) for interactive exploration.

## 👩‍💻 Author

Kanisha Sharma

✨ If you like this project, don’t forget to ⭐ star the repo!
