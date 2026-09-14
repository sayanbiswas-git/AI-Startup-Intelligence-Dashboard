# AI Startup Intelligence & Venture Benchmark Dashboard

An executive-level market intelligence project benchmarking **35 leading global artificial intelligence companies** as of **September 2026**[cite: 9, 10]. This project aggregates, analyzes, and visualizes over **$84.8B in total funding** and **$437.4B in tracked market valuation** across frontier model developers, infrastructure providers, and vertical AI tooling[cite: 9, 10].

---

## 📌 Executive Summary

* **Tracked Entities:** 35 private and venture-backed AI companies[cite: 9, 10]
* **Total Tracked Funding:** $84,860,500,000[cite: 9, 10]
* **Total Portfolio Valuation:** $437,447,000,000[cite: 9]
* **Average Founding Year:** 2020[cite: 9, 10]
* **Average Funding per Company:** $2,424,585,714[cite: 9, 10]

---

## 📊 Key Market Insights

### 1. Sector Capitalization & Concentration
* **Foundation Models Lead:** The **Large AI Models** category dominates capital deployment, capturing **$53.4B (63.0%)** of total tracked funding across 7 key players, averaging **$7.64B per company**[cite: 9, 10].
* **Compute Infrastructure:** **AI Infrastructure** (e.g., CoreWeave) ranks second with **$20.27B raised**, highlighting the high capital intensity of GPU compute and data pipeline scaling[cite: 9, 10].
* **Application Layers:** AI Coding ($7.39B), AI Image & Video ($2.35B), and AI Agents ($1.40B) represent fast-growing specialized segments with leaner average capital requirements[cite: 9, 10].

### 2. Geographic Distribution (HQ)
* **United States:** Dominates venture deployment with **77.1% of startups (27 companies)** and **$74.35B (87.6%)** of total capital raised[cite: 9, 10].
* **Global Ecosystems:** China holds **$7.4B** (anchored by DeepSeek)[cite: 9, 10], followed by France (**$1.14B**), Canada (**$1.07B**), Israel (**$393M**), Germany (**$331M**), and the United Kingdom (**$181M**)[cite: 9, 10].

### 3. Top Market Leaders

| Rank | Company | Category | Valuation (USD) | Total Funding (USD) |
| :---: | :--- | :--- | :---: | :---: |
| **1** | OpenAI | Large AI Models | $157,000,000,000 | $21,900,000,000 |
| **2** | DeepSeek | Large AI Models | $59,200,000,000 | $7,400,000,000 |
| **3** | Anthropic | Large AI Models | $40,000,000,000 | $9,700,000,000 |
| **4** | xAI | Large AI Models | $40,000,000,000 | $12,000,000,000 |
| **5** | Anysphere (Cursor) | AI Coding | $29,300,000,000 | — |
| — | CoreWeave | AI Infrastructure | — | $14,000,000,000 |

---

## 🛠️ Tech Stack & Methodology

* **Data Modeling & Cleaning:** Microsoft Excel / Python (Pandas) — Schema normalization, missing value imputation, and currency conversions.
* **Aggregations & Logic:** Pivot Tables, dynamic lookups (`XLOOKUP`), and summary KPI aggregations.
* **Visualization:** Custom executive dashboard reporting (Power BI / Tableau / Excel BI) incorporating category breakdown charts, geographic share distributions, and dynamic Top-N leaderboards[cite: 9, 10].

---

## 📂 Repository Structure

```text
├── data/
│   ├── ai_startups_raw.csv          # Raw data extract (35 companies)
│   └── ai_startups_cleaned.csv      # Processed data with normalized financials
├── dashboard/
│   ├── AI_Startup_Intelligence.pdf  # High-resolution dashboard export
│   └── AI_Startup_Intelligence.xlsx # Dynamic workbook with pivot tables
├── README.md                        # Documentation and executive summary
