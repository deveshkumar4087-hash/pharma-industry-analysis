# 🔬 AI-Driven Pharmaceutical Market Intelligence & Demand Forecasting

> A mini consulting project combining global health data, market analytics, and predictive forecasting to uncover pharmaceutical market opportunities.

---

## 📁 Project Structure

```
AI-Pharma-Market-Intelligence/
│
├── data/
│   ├── global_health_dataset.csv      # Combined global health + pharma dataset (1,080 rows)
│   └── forecast_results.csv           # Model output: 2024–2030 demand forecasts
│
├── notebooks/
│   └── market_intelligence_analysis.ipynb   # Full EDA + forecasting pipeline
│
├── visualizations/
│   ├── disease_trend.png              # Global disease prevalence trends (2015–2023)
│   ├── drug_demand_trend.png          # Drug demand by therapy area
│   ├── regional_market.png            # Regional market intelligence (4-panel)
│   └── demand_forecast.png            # 5-year forecast per disease (2024–2030)
│
├── dashboard/
│   └── pharma_market_dashboard.html   # Interactive web dashboard
│
├── README.md
└── insights.md                        # Analyst-grade business insights
```

---

## 📊 Dataset Overview

| Column | Description |
|---|---|
| Country | 15 countries across 6 regions |
| Year | 2015–2023 (9 years) |
| Disease | 8 therapy areas |
| Prevalence_Pct | Disease prevalence as % of population |
| Drug_Sales_USD | Annual pharmaceutical sales in USD |
| Healthcare_Spending_GDP_Pct | National healthcare spend as % of GDP |
| Population_M | Country population in millions |
| Region | Geographic region |
| Market_Type | Emerging vs Established market |

**Data Sources Modeled After:** WHO Global Disease Burden, World Bank Healthcare Expenditure, IQVIA Pharma Sales Data

---

## 🚀 Getting Started

```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Launch notebook
jupyter notebook notebooks/market_intelligence_analysis.ipynb
```

---

## 🔑 Key Findings

- **Oncology** is the highest-value therapy area, projected to reach **$193.8B by 2030**
- **Emerging markets** (India, China, Nigeria) show **2–3× higher CAGR** than established markets
- **Strong positive correlation** (r > 0.7) between healthcare spending and drug demand
- **Diabetes** shows the most predictable growth trajectory (R² = 0.954)

---

## 🛠️ Tech Stack

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Scikit-learn` · `HTML/CSS/JS`

---

## 👤 Author - DEVESH

Built as a pharmaceutical market intelligence consulting project.
