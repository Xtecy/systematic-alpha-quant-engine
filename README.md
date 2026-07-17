Here is a complete, professional, and visually striking `README.md` custom-tailored for your GitHub repository. It perfectly frames the quantitative depth of your project to anyone looking at your profile.

---

# 🤖 Systematic Alpha: Automated Quant Execution Engine & Risk Model

An institutional-grade algorithmic trading implementation and quantitative risk framework engineered for automated breakout trading on the Nasdaq 100 Index ($US100$). The system integrates high-frequency execution architecture in MQL5 with an end-to-end Python stress-testing pipeline to maximize statistical expectancy while enforcing absolute capital preservation.

---

## 📊 Core Performance Metrics

Through rigorous multi-dimensional parameter grid optimization over a **2.2-year historical testing window** spanning high-volatility regimes, tech rotations, and structural shifts, the system achieved a highly robust equity distribution:

| Metric | System Output | Institutional Benchmarks |
| --- | --- | --- |
| **Win Rate** | **58.26%** (208 Wins / 149 Losses) | > 52.0% (System Alpha) |
| **Profit Factor** | **1.29** ($12,944.94 Gross Profit) | 1.20 - 1.50 (Stable Edge) |
| **Trade Expectancy (EV)** | **$8.25 per execution** | Positive Mathematical Expectancy |
| **Sample Size** | **357 Closed Round-Trip Trades** | > 100 (Statistically Significant) |
| **Max Peak-to-Trough Drawdown** | **$743.78** (Fixed) / **$851.54** (Compounding) | < $1,000.00 (Prop Firm Hard Buffer) |

---

## 🛠️ Key Architectural Features

### ⚡ 1. MQL5 Automated Execution Engine

* **Microstructural Momentum Capture:** Dynamically maps out the 5-Minute Opening Range Breakout (ORB) volatility expansion immediately following the Nasdaq market open.
* **Granular Stop Management:** Utilizes a highly calibrated 1:1 Risk-to-Reward profile using raw asset price subtraction vectors rather than static point arrays to entirely neutralize broker decimal formatting variations.
* **Gated Execution Pipeline:** Built-in programmatic time filters restricts the engine to **exactly 1 execution per day** (16:30 – 17:00 window), neutralizing over-trading, revenge-trading, and toxic session churn.

### 📈 2. Mathematical Capital Scaling Model

* **Dynamic Equity Compounding:** Implements a strict $1\%$ capital risk variable parameter based on floating equity value.
* **Asymmetrical Risk Mitigation:** Leveraging the **Static $9,000 Capital Floor** ruleset common in modern proprietary firm accounts, the compounding logic operates as an anti-fragile cushion: lot sizes expand during positive drift to accelerate payout timelines, and scale *downward* during drawdown cycles to systematically widen the distance to the maximum loss limit.

### 🧪 3. Python Stochastic Stress-Testing Pipeline

* **Resampling & Shuffling Simulator:** Contains an end-to-end Monte Carlo simulation pipeline developed using `Pandas` and `NumPy` inside Jupyter Notebooks.
* **Ruin Probability Analysis:** Shuffles historical chronological data points across $10,000+$ randomized paths to expose localized consecutive loss clustering.
* **Quantified Payout Horizons:** The stochastic model calculates a **97.75% mathematical success probability** of hitting target distributions with a quantified **median expectancy window of 29 trading days** to payout status under fixed-frequency rulesets.

---

## 📂 Project Structure

```text
├── ExpertAdvisors/
│   └── Nasdaq_ORB_Breakout_v5.mq5     # Production MQL5 execution engine source code
├── Notebooks/
│   └── Risk_Stress_Testing.ipynb      # Monte Carlo simulations & resampling analytics
├── Analytics/
│   ├── Weekly_PnL_Breakdown.csv       # 118-week aggregated performance data
│   └── Monthly_PnL_Breakdown.csv      # Macro distribution data logs
├── .gitignore                         # Prevents tracking giant raw binary tick files
└── README.md                          # Project overview and system documentation

```

---

## 🚀 Getting Started

### Prerequisites

To run the automated execution engine, you need **MetaTrader 5 Terminal**. To run the risk analytics pipeline locally via VS Code or Google Colab, initialize your terminal with the required data libraries:

```bash
pip install pandas numpy matplotlib openpyxl xlsxwriter

```

### Running the Analytics Pipeline

1. Clone the repository to your local workspace.
2. Export your historical closed transaction logs from MetaTrader 5 as a CSV file.
3. Place the CSV file into your local project directory and launch `Risk_Stress_Testing.ipynb` inside VS Code to instantly generate customized Monte Carlo trajectory paths and macro performance charts.

---

## 📈 Macro-Performance Visualizations

### Weekly & Monthly Performance Drift

The project engine automates data parsing matrices to compress volatile daily tick changes into smooth, actionable performance horizons. Out of 28 structural market months under test, the system demonstrates consistent macro stability, absorbing drawdowns effectively through strict risk alignment:

* **Average Weekly Profit Baseline:** `$28.10`
* **Historical Peak Weekly Capture:** `$430.93`

---

## ⚖️ Disclaimer

*This repository contains an academic quantitative research project and data modeling framework. Past performance does not guarantee future live market results. All system parameters are deployed at the sole risk of the operator.*
