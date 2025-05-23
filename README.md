# 📈 Algorithmic Trading with Machine Learning & Quant Strategies

This project demonstrates a complete end-to-end pipeline for constructing a machine learning-based trading strategy. From data acquisition to clustering, portfolio optimization, and performance evaluation, the workflow integrates key quantitative finance and machine learning techniques.

---

## 🚀 Project Highlights

- **End-to-end workflow**: Covers all steps from data acquisition to portfolio optimization and performance evaluation.
- **Unsupervised learning**: Utilizes K-Means clustering to group stocks by technical and fundamental features.
- **Portfolio optimization**: Allocates capital using the Efficient Frontier (max Sharpe ratio).
- **Comprehensive analysis**: Benchmarks strategy returns against the S&P 500, with rich visualizations.

---

## 📁 Repository Structure

| File/Folder | Description |
|-------------|-------------|
| `.gitignore` | Specifies files and folders to be ignored by Git |
| `Algorithmic_Trading_Machine_Learning_Quant_Strategies.ipynb` | Main Jupyter notebook with all code and analysis |
| `requirements.txt` | List of Python dependencies |
| `README.md` | Project documentation (this file) |

---

## 🧠 Methodology Overview

### 1. Data Acquisition
- Downloads historical price data for all S&P 500 stocks.
- Retrieves Fama-French factor data for enhanced feature engineering.

### 2. Feature Engineering
- Computes technical indicators: volatility, RSI, Bollinger Bands, ATR, MACD, and more.
- Aggregates data monthly and filters for the top 150 most liquid stocks.
- Calculates rolling returns over multiple time horizons.

### 3. Clustering & Portfolio Construction
- Applies K-Means clustering to group stocks with similar profiles each month.
- Selects assets from clusters and constructs a portfolio using Efficient Frontier optimization (max Sharpe ratio).

### 4. Performance Evaluation
- Compares the strategy's returns to a buy-and-hold S&P 500 strategy.
- Visualizes cumulative returns and other key performance metrics.

---

## ⚙️ Requirements

Install all dependencies with:

```bash
pip install -r requirements.txt
