# Treasury-Management-Dashboard
# 💰 Treasury Management Dashboard (Educational Simulation)

### 🎯 Objective  
This project simulates the **core analytical workflow of a corporate treasury department** — from raw cashflow data to executive dashboards.  
It integrates **liquidity monitoring, working capital analysis, scenario forecasting, and FX exposure**, using a simplified but realistic dataset.

The goal is to **recreate the end-to-end pipeline** a Treasury Analyst would manage in a corporate environment (e.g., Repsol, Siemens Energy, BBVA Treasury), and to visualize key insights in **Power BI** and a **professional PDF report**.

> ⚙️ *This project is purely educational. It does not use real company data but aims to mirror professional financial analysis and visualization standards.*

---

## 🧩 Project Overview

| Module | Description | Main KPIs |
|--------|--------------|-----------|
| **Liquidity & Cashflow** | Tracks inflows, outflows, and closing cash positions over time | Free Cash Flow (FCF), Net Cash Flow, Cash Buffer |
| **Working Capital Efficiency** | Measures operational liquidity and efficiency | CCC, DSO, DPO, DIO, Liquidity Ratio, Quick Ratio |
| **FX Exposure** | Simulates exposure to foreign currencies | Net FX Impact, % USD Flows |
| **Scenario Forecast** | Projects liquidity under base, optimistic, and pessimistic scenarios | Forecasted Closing Cash, Liquidity Gap, Stress Impact |

---

## ⚙️ Tools & Techniques
- **Excel** — Financial modeling, ratio computation, forecasting logic.
- **Power BI** — Data visualization and executive dashboarding.
- **Power Query / DAX (basic)** — Data transformations and KPI measures.
- **Financial Concepts** — Liquidity analysis, working capital cycles, solvency metrics, scenario analysis.

---

## 📂 Project Structure


---

## 🧮 Simplifications & Assumptions

To maintain clarity and educational value:
- The **debt schedule** module was excluded to keep relationships simple.  
  Interest coverage is calculated using a **proxy** (3.5 % of total debt or 45 % of financing outflows) to simulate interest expense.
- Data is **synthetic** but scaled realistically (values in € millions).
- Forecasts are **manually simulated** using constant growth rates and scenario multipliers.
- Depreciation & amortization are **omitted**; `Operating Inflows – Operating Outflows` serves as an **EBITDA proxy**.

These simplifications preserve the *analytical essence* of treasury management while keeping the model reproducible and pedagogically clean.

---

## 📊 Expected Outputs

### 🟩 Power BI Dashboard

#### **Page 1 – Liquidity Overview**
- **Cards:** Cash (Last), Net Cash Flow, FCF, Cash Buffer  
- **Charts:**  
  - Line: *Cash Balance Over Time*  
  - Waterfall: *Inflows vs Outflows*  
  - Bar: *Net Cash Flow by Month*  
- **Slicer:** Year  

🧠 *Insight:* “Liquidity remains stable with a 2.5-month cash buffer. Peaks and troughs correspond to CapEx and financing activities.”

---

#### **Page 2 – Working Capital & Efficiency**
- **Cards:** Liquidity Ratio, Quick Ratio, CCC  
- **Charts:**  
  - Bar: *DSO vs DPO vs DIO*  
  - Line: *CCC Trend*  
  - Stacked Bar: *Working Capital Components*  

🧠 *Insight:* “CCC improved by 8 days YoY due to faster collections and reduced inventory levels.”

---

#### **Page 3 – FX & Risk Overview**
- **Cards:** % USD Flows, FX Net Impact (€)  
- **Charts:**  
  - Line: *EUR/USD Trend*  
  - Pie: *FX Flow Distribution by Currency*  
  - Bar: *FX Net Exposure Over Time*  

🧠 *Insight:* “USD exposure represents 25 % of total flows; a +5 % EUR/USD appreciation would reduce net cash by 2 %.”

---

#### **Page 4 – Forecast & Scenarios**
- **Cards:** Forecasted Cash (Base), Liquidity Gap (Pessimistic vs Base), Projected Interest Expense  
- **Charts:**  
  - Multi-line: *Forecasted Cash Balance (3 scenarios)*  
  - Table: *KPI comparison across scenarios*  
  - Waterfall: *Sensitivity by driver (Revenue, COGS, Interest Rate, CapEx)*  

🧠 *Insight:* “Under pessimistic conditions, liquidity falls –12 %, but the cash buffer remains above 1.1× operating expenses.”

---

### 🧾 **Final Output – Executive Report (PDF)**
A one-page visual summary consolidating:
- Key metrics (Cash, FCF, Liquidity Ratio, CCC, FX Exposure)  
- Combined *Historical + Forecast* cash balance chart  
- Scenario comparison table  
- 2–3 key takeaways in concise management tone.  

> 💼 *Purpose:* to replicate how Treasury & FP&A teams report liquidity and cash-risk insights to senior management or CFOs.

---

## 🧠 Educational Purpose

This project was built independently to:
- Demonstrate **understanding of corporate treasury mechanisms**,  
- Practice **data transformation and visualization**,  
- Build a portfolio example linking **financial logic + analytical presentation**.

It is **not a financial advice or real company report**, but an *academic simulation* for learning purposes.

---

## ✍️ Author

**[Your Name]**  
MSc Financial Management | UC3M Economics  
Siemens Energy (Finance Excellence Intern)  
Focused on Treasury Analytics, Quantitative Finance, and Data Visualization.

📎 [LinkedIn](https://linkedin.com/in/yourprofile) · [GitHub](https://github.com/yourusername)

---

## 📈 Next Steps
- Add a simplified **Debt module** in a future version.  
- Integrate with **Python** for Monte Carlo liquidity stress tests.  
- Expand FX risk analysis using real EUR/USD data from FRED.

---

