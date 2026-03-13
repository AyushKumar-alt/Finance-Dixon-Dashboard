# Financial Ratio Analysis Dashboard — Dixon vs Honeywell Automation

An interactive financial dashboard comparing key financial ratios of two BSE-listed companies — **Dixon Technologies** and **Honeywell Automation India** — across five fiscal years (Mar-21 to Mar-25).

Built to support investment-style financial analysis through dynamic visualizations and real-time metric filtering.

---

## 🔍 Overview

Financial ratio analysis is a core tool in investment research and equity analysis. This dashboard enables side-by-side comparison of Dixon and Honeywell across three ratio categories, helping identify trends in liquidity, profitability, and operational efficiency over time.

| Company | Sector | Listed On |
|---|---|---|
| Dixon Technologies | Electronics Manufacturing | BSE / NSE |
| Honeywell Automation India | Industrial Automation | BSE / NSE |

---

## 📈 Metrics Covered

**Liquidity Ratios**
- Current Ratio
- Quick Ratio

**Profitability Ratios**
- Gross Profit Margin (%)
- Net Profit Margin (%)

**Turnover Ratios**
- Inventory Turnover
- Asset Turnover
- Trade Receivable Turnover

---

## ⚙️ Features

- **Company filter** — View Dixon, Honeywell, or both simultaneously
- **Metric group selector** — Switch between Liquidity, Profitability, and Turnover
- **Year range slider** — Narrow analysis to any sub-period within Mar-21 to Mar-25
- **KPI cards** — Latest values for all key metrics at a glance
- **Grouped bar chart** — Primary visualization with value labels
- **Trend sparkline** — Line chart tracking the primary metric over selected range
- **Raw data table** — CSV-style output of all visible data points

---

## 🧠 Key Insights

- **Dixon** operates on thin margins (~2–4% NPM) but compensates with high asset turnover (2.3–2.6x), typical of a contract manufacturer
- **Honeywell** maintains significantly higher margins (~12–15% NPM) with stronger liquidity (Current Ratio 3.4–3.7x), reflecting a premium B2B solutions model
- Dixon's inventory turnover (~10–15x) vs Honeywell's declining trend (~18–32x) reveals differences in supply chain and business model
- Trade receivable turnover divergence (Dixon ~8–12x vs Honeywell ~3–4x) suggests different credit and collection cycles

---

## 🛠️ Tech Stack

- **HTML / CSS / JavaScript** — Frontend
- **Plotly.js** — Interactive charts and sparklines
- **Google Fonts (Inter)** — Typography

No backend or build tools required — runs entirely in the browser.

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/yourusername/financial-dashboard-dixon-honeywell.git

# Open in browser
open index.html
```

Or simply open `index.html` directly in any modern browser — no server needed.

---

## 📁 Project Structure

```
financial-dashboard/
│
├── index.html        # Main dashboard (self-contained)
└── README.md         # Project documentation
```

---

## 📌 Data Source

Financial data sourced from publicly available annual reports and BSE filings for Dixon Technologies and Honeywell Automation India (FY2021–FY2025).

---

## 👤 Author

**Ayush Kumar**  
B.Tech CSE (Data Science) | Finance Minor — Vidyashilp University  
[LinkedIn](https://linkedin.com/in/ayush-kumar) · [Portfolio](https://ayush.portfolio.netlify.app)
