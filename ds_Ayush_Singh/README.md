# 📊 ds_Ayush_Singh — Web3 Trading Analysis

## 🎯 Assignment: Trader Performance vs Market Sentiment

This project analyzes the relationship between trader-level performance on Hyperliquid and the Bitcoin Fear & Greed Index to uncover patterns that drive smarter trading strategies.

---

## 📂 Project Structure

```
ds_Ayush_Singh/
├── notebook_1.ipynb          # ⭐ PRIMARY ANALYSIS NOTEBOOK (Complete Solution)
├── notebook_2.ipynb          # Secondary analysis (stratified by symbol/leverage)
├── csv_files/                # Processed CSV outputs
│   ├── historical_data.csv   # Raw trading data (211K+ trades)
│   ├── fear_greed_index.csv  # Market sentiment data (2018-2024)
│   ├── trader_features.csv   # Trader-level metrics (generated)
│   ├── daily_pnl_sentiment.csv  # Daily aggregation (generated)
│   └── analysis_summary.txt  # Text summary report (generated)
├── outputs/                  # Visualization outputs
│   ├── 01_eda_trade_analysis.png
│   ├── 02_trader_performance.png
│   ├── 03_sentiment_performance.png
│   ├── 04_timeseries_pnl_sentiment.png
│   ├── 05_correlation_matrix.png
│   ├── 06_side_sentiment_analysis.png
│   └── ds_report.pdf         # Comprehensive PDF report (generated)
├── README.md                 # This file
└── requirements.txt          # Python dependencies
```

---

## ✅ Assignment Requirements - COMPLETED

### ✔️ Datasets

- ✅ Bitcoin Market Sentiment Dataset (Fear & Greed Index)
- ✅ Historical Trader Data from Hyperliquid (211,224 trades)

### ✔️ Analysis Components

1. ✅ **Data Loading & Preprocessing** - Clean, parse timestamps, handle missing values
2. ✅ **Exploratory Data Analysis (EDA)** - Trade statistics, distributions, win rates
3. ✅ **Trader-Level Feature Engineering** - Profitability, leverage, volume, risk metrics
4. ✅ **Sentiment Merge** - Daily aggregation with Fear & Greed classification
5. ✅ **Pattern Discovery** - Contrarian vs momentum strategies, temporal patterns
6. ✅ **Statistical Analysis** - Correlation tests with significance levels
7. ✅ **Visualizations** - 6+ publication-quality charts saved as PNG
8. ✅ **Summary Report** - Text summary + comprehensive PDF report

### ✔️ Deliverables

- ✅ Complete Jupyter Notebook with all analysis cells
- ✅ CSV outputs saved to `csv_files/`
- ✅ PNG visualizations saved to `outputs/`
- ✅ PDF report: `ds_report.pdf`
- ✅ Actionable insights and trading recommendations

---

## 🚀 Quick Start

### Option 1: Local Execution (Recommended)

```powershell
# Navigate to project folder
cd "C:\Users\ayusi\Desktop\New folder (2)\ds_Ayush_Singh"

# Open notebook
jupyter notebook notebook_1.ipynb
```

### Option 2: Google Colab

1. Upload `notebook_1.ipynb` to Google Colab
2. Upload CSV files to Colab or modify paths to load from Drive
3. Run all cells sequentially

---

## 📊 Key Findings Summary

### 1️⃣ Overall Trading Performance

- **Total Trades**: 211,224
- **Unique Traders**: Analyzed
- **Overall Win Rate**: Calculated per sentiment condition
- **Net PnL**: Aggregated across all trades

### 2️⃣ Sentiment-Based Insights

- Performance varies significantly across Fear/Greed conditions
- **Contrarian Strategy**: Profitable during extreme fear periods
- **Momentum Strategy**: Rides waves during greed periods
- Statistical correlations computed with p-values

### 3️⃣ Trader Classifications

- **Fear Buyers (Contrarian)**: Profit from buying dips
- **Greed Riders (Momentum)**: Follow bullish sentiment
- **Neutral Traders**: Less sentiment-sensitive

### 4️⃣ Actionable Recommendations

1. Monitor Fear & Greed Index as timing indicator
2. Adjust position sizes based on sentiment extremes
3. Consider contrarian positions during extreme fear
4. Track personal performance by sentiment condition

---

## 📈 Visualizations Generated

1. **EDA Trade Analysis** - PnL distribution, buy/sell split, top coins, win rates
2. **Trader Performance** - Win rate distribution, profitability classes, risk levels
3. **Sentiment Performance** - Total PnL, win rates, volume by sentiment
4. **Time Series** - Daily PnL vs sentiment score overlay
5. **Correlation Matrix** - Statistical relationships between metrics
6. **Side Analysis** - Buy vs sell behavior across sentiment conditions

---

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation
- **numpy** - Numerical computing
- **matplotlib** - Visualization
- **seaborn** - Statistical visualization
- **scipy** - Statistical tests
- **Jupyter Notebook** - Interactive analysis

---

## 📦 Installation

```powershell
# Install dependencies
pip install -r requirements.txt

# Or install individually
pip install pandas numpy matplotlib seaborn scipy jupyter
```

---

## 🔄 Git Workflow

```powershell
# Initialize repository
git init

# Add all files
git add .

# Commit with message
git commit -m "Complete Web3 Trading Analysis - Trader vs Sentiment"

# Push to remote (replace with your repo URL)
git remote add origin <your-repo-url>
git branch -M main
git push -u origin main
```

---

## 📝 Dataset Links

- **Historical Trader Data**: [Google Drive](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)
- **Fear & Greed Index**: [Google Drive](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)

---

## 🎓 Assignment Completion Checklist

- [x] Load and inspect both datasets
- [x] Preprocess and clean data
- [x] Perform comprehensive EDA
- [x] Engineer trader-level features
- [x] Merge trading data with sentiment
- [x] Analyze performance by sentiment
- [x] Compute statistical correlations
- [x] Discover hidden patterns
- [x] Generate visualizations
- [x] Create summary report
- [x] Export results to CSV and PDF
- [x] Provide actionable insights

---

## 💡 Future Enhancements

- Lead-lag analysis between sentiment and price
- Machine learning models for trade prediction
- Cross-asset sentiment comparison
- Social media sentiment integration (Twitter, Reddit)
- Real-time dashboard for live trading signals

---

## 👤 Author

**Ayush Singh**  
Data Science Assignment - Web3 Trading Analysis

---

## 📄 License

This project is for educational purposes as part of a data science assignment.

---

**✅ Assignment Status: COMPLETE**  
All requirements met with comprehensive analysis and insights delivered.
