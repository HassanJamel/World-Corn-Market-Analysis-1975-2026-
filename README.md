<p align="center">
  <a href="https://www.kaggle.com/code/hassanjameelahmed/world-corn-market-analysis-1975-2026" target="_blank">
    <img src="Global Corn Supply and Demand.png" alt="Global Corn Supply and Demand" width="800">
  </a>
</p>

[project.md](https://github.com/user-attachments/files/24931100/project.md)
# 🌽 Global Corn Supply & Demand Master Analysis (1975-2026)

## _50 Years of Agricultural Market Insights_

[![Python](https://img.shields.io/badge/Python-3.9+-3776ab?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Plotly](https://img.shields.io/badge/Plotly-5.0+-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com)
[![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com)

---

## 📋 Table of Contents

1. [Project Overview](#-project-overview)
2. [SEO-Optimized Project Name](#-seo-optimized-project-name)
3. [Kaggle Tags](#-top-5-kaggle-tags)
4. [Dataset Description](#-dataset-description)
5. [Key Features](#-key-features)
6. [Problems & Challenges](#-problems--challenges)
7. [Usage Guide](#-usage-guide)

---

## 🎯 Project Overview

This comprehensive data science project provides an in-depth **Exploratory Data Analysis (EDA)** of the global corn supply and demand landscape spanning **50 years** (1975-2026). The analysis covers the complete agricultural marketing year cycle, examining production trends, consumption patterns, trade dynamics, and stock fluctuations.

### 🌟 What Makes This Project Unique?

- **Historical Depth**: Half a century of continuous agricultural data
- **Complete Supply Chain**: From production to final consumption
- **Professional Visualizations**: Interactive Plotly charts and statistical plots
- **Real-World Insights**: Actionable intelligence for agricultural economists, traders, and policymakers

---

## 🔍 SEO-Optimized Project Name

### Primary Title:

**"Global Corn Supply & Demand Master Analysis (1975-2026) | 50 Years of Agricultural Market Insights"**

### Alternative SEO-Friendly Titles:

1. "Comprehensive Corn Market Analysis: 50 Years of Supply & Demand Data (1975-2026)"
2. "World Corn Production & Consumption Trends: A Half-Century Analysis"
3. "Agricultural Commodities Deep Dive: Global Corn Supply Chain Dataset"
4. "US Corn Market Historical Analysis: From Farm to Export (1975-2026)"

### Keywords for Discovery:

`corn production data`, `maize supply chain analysis`, `agricultural commodities dataset`, `USDA corn statistics`, `grain market trends`, `corn consumption patterns`, `agricultural EDA`, `food security analysis`, `commodity price factors`, `crop yield analysis`

---

## 🏷️ Top 5 Kaggle Tags

| Priority | Tag                         | Relevance                                                        |
| :------: | --------------------------- | ---------------------------------------------------------------- |
|    1️⃣    | `agriculture`               | Primary domain - directly relates to crop production and farming |
|    2️⃣    | `time-series-analysis`      | 50-year longitudinal data perfect for temporal analysis          |
|    3️⃣    | `exploratory-data-analysis` | Core methodology featuring comprehensive EDA                     |
|    4️⃣    | `commodities`               | Corn is a major globally-traded commodity                        |
|    5️⃣    | `supply-chain`              | Complete supply-to-demand data flow coverage                     |

### Supplementary Tags:

- `economics`
- `food`
- `usa`
- `data-visualization`
- `descriptive-statistics`

---

## 📊 Dataset Description

### File Information

| Attribute      | Value                     |
| -------------- | ------------------------- |
| **Filename**   | `corn_annual_summary.csv` |
| **Records**    | 46 marketing years        |
| **Time Range** | 1975/76 - 2025/26         |
| **Features**   | 12 columns                |
| **File Size**  | ~6 KB                     |

### Column Definitions

| Column               | Type   | Unit            | Description                                  |
| -------------------- | ------ | --------------- | -------------------------------------------- |
| `marketing_year`     | String | Year            | USDA marketing year (Sept-Aug)               |
| `quarter_period`     | String | -               | Marketing year period identifier             |
| `beginning_stocks`   | Float  | Million Bushels | Inventory at start of marketing year         |
| `production`         | Float  | Million Bushels | Total corn production volume                 |
| `imports`            | Float  | Million Bushels | Corn imported from foreign sources           |
| `total_supply`       | Float  | Million Bushels | Sum: beginning_stocks + production + imports |
| `industrial_use`     | Float  | Million Bushels | Ethanol, starch, sweeteners, etc.            |
| `seed_use`           | Float  | Million Bushels | Corn used for planting                       |
| `feed_residual`      | Float  | Million Bushels | Animal feed + statistical adjustments        |
| `total_domestic_use` | Float  | Million Bushels | Sum of all domestic consumption              |
| `exports`            | Float  | Million Bushels | Corn exported to foreign markets             |
| `total_use`          | Float  | Million Bushels | domestic use + exports                       |
| `ending_stocks`      | Float  | Million Bushels | Inventory at end of marketing year           |

---

## 🔑 Key Features

### 📈 Analysis Highlights

1. **Supply Side Analysis**
   - Production trends over 50 years
   - Import patterns and dependencies
   - Stock level dynamics

2. **Demand Side Analysis**
   - Industrial use growth (especially ethanol boom post-2005)
   - Feed consumption patterns
   - Export market evolution

3. **Market Equilibrium**
   - Supply-demand balance indicators
   - Ending stocks as market tightness measure
   - Price implication signals

---

## ⚠️ Problems & Challenges

### 🔴 Data Quality Challenges

| Issue                | Description                                                                   | Impact                                      | Mitigation                        |
| -------------------- | ----------------------------------------------------------------------------- | ------------------------------------------- | --------------------------------- |
| **Missing Years**    | Some marketing years are absent (1981/82, 1991/92, 2001/02, 2011/12, 2021/22) | Breaks in time series continuity            | Interpolation or acknowledge gaps |
| **Data Aggregation** | Annual data loses seasonal/quarterly patterns                                 | Limited granularity for short-term insights | Focus on long-term trends         |
| **Single Source**    | Likely USDA-sourced data, single perspective                                  | Potential regional bias                     | Acknowledge US-centric view       |

### 🟡 Analytical Challenges

| Challenge                    | Description                                                            | Solution Approach                          |
| ---------------------------- | ---------------------------------------------------------------------- | ------------------------------------------ |
| **No Price Data**            | Supply/demand quantities without price context                         | Interpret through stocks-to-use ratios     |
| **External Factors Missing** | Weather, policy changes, oil prices not included                       | Qualitative discussion of known events     |
| **Future Projections**       | 2025/26 data is forecast, not actual                                   | Flag as projected and interpret cautiously |
| **Unit Consistency**         | All in million bushels, metric conversion needed for global comparison | Provide conversion notes where relevant    |

### 🟠 Interpretation Challenges

1. **Ethanol Boom Impact**: Post-2005 industrial use surge requires historical context about Renewable Fuel Standard
2. **Export Volatility**: Trade policy changes (China relations, trade wars) create outliers
3. **Feed Residual Category**: Contains both actual feed use AND statistical discrepancy - interpretation requires caution
4. **COVID-19 Impact**: 2020/21 and 2021/22 years may contain pandemic disruption effects

### 🔧 Technical Considerations

```
📌 Note for Analysts:
- Marketing year runs Sept-Aug, not calendar year
- "Residual" in feed_residual includes measurement error
- Ending stocks = Beginning stocks for next year
- 2025/26 is a projection, subject to revision
```

---

## 📖 Usage Guide

### Quick Start

```python
import pandas as pd

# Load the dataset
df = pd.read_csv('corn_annual_summary.csv')

# Basic exploration
print(df.shape)
print(df.info())
print(df.describe())
```

### Recommended Analysis Path

1. **Start with** → `New_App.ipynb` notebook for complete EDA
2. **Focus on** → Time series trends in production and usage
3. **Key metrics** → Stocks-to-use ratio, production growth rate
4. **Visualize** → Interactive Plotly charts for trend exploration

---

## 👤 Author

**Eng. Hassan Jameel**

- 📧 Data Science & Agricultural Analytics
- 📅 Last Updated: January 2026

---

## 📜 License

This dataset analysis is provided for educational and research purposes.

---

_🌽 "Corn is not just a crop, it's the foundation of modern agriculture and food security."_
