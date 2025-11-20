# 💰 Treasury Management Dashboard (Educational Simulation)

### 🎯 Objective  
This project simulates the **core analytical workflow of a corporate treasury department** — from raw cashflow data to executive dashboards.  
It integrates **liquidity monitoring, working-capital analysis, and scenario forecasting** using a simplified but realistic dataset.

The goal is to **recreate the end-to-end pipeline** a Treasury Analyst would manage in a corporate environment (e.g., Repsol, Siemens Energy, BBVA Treasury), and to visualize key insights in **Power BI**.

> ⚙️ *This project is purely educational. It does not use real company data but aims to mirror professional financial analysis and visualization standards.*

---

## 🧩 Project Overview

| Module | Description | Main KPIs |
|--------|-------------|-----------|
| **Liquidity & Cashflow** | Tracks inflows, outflows, and closing cash positions over time | FCF, Net Cash Flow, Cash Buffer |
| **Working Capital Efficiency** | Measures operational liquidity and efficiency | CCC, DSO, DPO, DIO, Liquidity Ratio, Quick Ratio |
| **Scenario Forecast (2026)** | Projects liquidity under different stress environments | Projected Closing Cash, Liquidity Gap, Interest Coverage |

---

## ⚙️ Tools & Techniques
- **Excel** — Financial modeling and scenario logic  
- **Power BI** — Dashboarding and visualization  
- **Power Query / DAX (basic)** — Data transformations and custom KPIs  
- **Financial Concepts** — Liquidity analysis, working capital cycles, solvency metrics, scenario analysis.

---

## 🧮 Simplifications & Assumptions

To maintain clarity and educational value:

- The **debt schedule** module was removed to avoid unnecessary complexity.
- Interest coverage is simulated using a **proxy expense** (3.5% of assumed debt or 45% of financing outflows).  
- Dataset is **synthetic**, but scaled to realistic industrial-sector magnitudes.  
- Forecasts are **scenario-based**, using constant growth rates and multipliers.  
- `Operating Inflows – Operating Outflows` acts as an **EBITDA proxy**.  
- Depreciation, amortization and taxes are not modeled.

These simplifications preserve core treasury logic while keeping the model clean and reproducible.

---

## 📊 Expected Outputs

---

### 🟩 **Dashboard 1 — Liquidity Overview (2024–2025)**

#### **Components**
- **Cards:**  
  - FCF_Total  
  - Net_Cash_Flow_Sum  
  - Cash_Buffer_Last  
  - Closing_Cash_Last  
- **Charts:**  
  - *Closing Cash Over Time* (line)  
  - *Inflows vs Outflows* (stacked bars)  
  - *Net Cash Flow by Month* (bar)  
- **Slicer:** Year (2024, 2025, 2026)

#### **Insight**  
Cash declines steadily during mid-2025 and stabilizes toward year-end. Operating inflows remain stable; financing outflows and capital spending drive the negative monthly swings.

---

### 🟩 **Dashboard 2 — Working Capital & Efficiency**

#### **Components**
- **Cards:**  
  - Quick_Ratio_Avg  
  - Liquidity_Ratio_Avg  
  - CCC_Avg  
- **Charts:**  
  - AR/AP/Inventory by quarter (stacked bars)  
  - CCC trend (line)  
  - DSO, DPO, DIO per quarter (bar groups)

#### **Insight**  
The CCC gradually improves over time, mainly due to lower DIO and more disciplined collections, while payables remain stable.

---

### 🟩 **Dashboard 3 — Scenario Forecast — 2026 Liquidity & Solvency**

#### **Components**
- **Cards:**  
  - Projected_Closing_Cash  
  - FCF_Avg_Scn  
  - Interest_Coverage_Scn  
  - Liquidity_Gap  
- **Charts:**  
  - Multi-scenario *Closing Cash Forecast* (Base, Optimistic, Pessimistic)  
  - Projected Closing Cash (bar comparison)  
  - Monthly inflows & outflows per scenario  
- **Table:** Scenario KPI summary

#### **Insight**  
The pessimistic scenario shows declining liquidity but remains above the minimum buffer threshold. The optimistic scenario produces strong cash accumulation and a healthy solvency margin.


## 🧠 Educational Purpose

This project was built independently to:
- Demonstrate **understanding of corporate treasury mechanisms**,  
- Practice **data transformation and visualization**,  
- Build a portfolio example linking **financial logic + analytical presentation**.

It is **not a financial advice or real company report**, but an *academic simulation* for learning purposes.

---

## ✍️ Author

**Enrique Ruiz de Almiron Da Silva**  
BSc Economics | UC3M   
Focused on Treasury Analytics, Quantitative Finance, and Data Visualization.

📎 [LinkedIn](https://linkedin.com/in/yourprofile) · [GitHub](https://github.com/yourusername)

---

## 📈 Next Steps
- Add a simplified **Debt module** in a future version.  
- Integrate with **Python** for Monte Carlo liquidity stress tests.  
- Expand FX risk analysis using real EUR/USD data from FRED.

---

