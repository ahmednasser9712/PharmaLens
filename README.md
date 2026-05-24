#  PharmaLens
> A comprehensive business intelligence and data analysis project for a pharmaceutical distribution company operating across 5 governorates in Egypt.

---

##  Project Overview

PharmaLens is a full-scale data analysis project designed to analyze 2 years **(2023–2024)** of real business operations for a pharma distribution company headquartered in **Kafrelsheikh, Egypt**.

The goal is to extract actionable insights, identify growth opportunities, reduce costs, and forecast 2025 performance — turning raw business data into strategic decisions.

---

##  Company Structure

```
HQ — Kafrelsheikh (Main Branch + Only Warehouse)
│
├── CEO
├── HR Manager
├── Accountant
├── Branch Manager
├── 5 Medical Reps (one per area)
└── 1 Collector
│
├── Cairo Branch
│   ├── Branch Manager
│   ├── 8 Medical Reps (one per area)
│   └── 1 Collector
│
├── Mansoura Branch
│   ├── Branch Manager
│   ├── 5 Medical Reps (one per area)
│   └── 1 Collector
│
├── Beheira Branch
│   ├── Branch Manager
│   ├── 5 Medical Reps (one per area)
│   └── 1 Collector
│
└── Gharbia Branch
    ├── Branch Manager
    ├── 5 Medical Reps (one per area)
    └── 1 Collector
```

**Total: 41 Employees** across all governorates
**28 Medical Reps** — one per area
**5 Collectors** — one per governorate
**54 Client Stores** — pharmacies, drug stores, medical stores, hospital pharmacies

---

##  Coverage Area

| Governorate | Areas Covered | No. of Stores |
|---|---|---|
| Kafrelsheikh (HQ) | Kafrelsheikh City, Desouk, Baltim, Fuwwah, Sidi Salem | 10 |
| Cairo | Nasr City, Heliopolis, Dokki, Downtown, Maadi, Zamalek, Ain Shams, Shubra | 15 |
| Mansoura | Mansoura City, Talkha, Mit Ghamr, Shirbin, Aga | 10 |
| Beheira | Damanhur, Kafr El Dawwar, Rashid, Abu Hummus, Edku | 9 |
| Gharbia | Tanta, Mahalla El Kubra, Zefta, Samanoud, Basyoun | 10 |

---

##  Products

| Medicine | Category | Buy Cost | Sell Price | Margin |
|---|---|---|---|---|
| Panadol 500mg | Analgesic | 18.50 EGP | 32.00 EGP | 42.2% |
| Metformin 850mg | Diabetes | 22.00 EGP | 38.50 EGP | 42.9% |
| Atorvastatin 20mg | Cardiology | 48.00 EGP | 85.00 EGP | 43.5% |
| Vitamin D3 1000IU | Supplement | 35.00 EGP | 62.00 EGP | 43.5% |

---

##  Project Structure

```
PharmaLens/
│
├── data/
│   └── Pharma_BI_Dataset_v3.xlsx        # Main dataset (10 sheets)
│
├── notebooks/
│   ├── 01_phase1_situation.ipynb        # Phase 1 — Current performance
│   └── 02_phase2_visualizations.ipynb  # Phase 2 — Charts & visualizations
│
├── visuals/
│   ├── 01_revenue_by_governorate.png
│   ├── 02_profit_by_medicine.png
│   ├── 03_monthly_trend.png
│   ├── 04_top_reps.png
│   ├── 05_debt_analysis.png
│   ├── 06_forecast_2025.png
│   ├── 07_expense_analysis.png
│   └── 08_executive_dashboard.png
│
├── outputs/
│   └── ...                              # Cleaned data & results
│
└── README.md
```

---

##  Dataset Sheets

| Sheet | Rows | Description |
|---|---|---|
| Sales Transactions | 11,713 | Every sale across 2 years |
| Stock Transfers | 384 | Shipments from HQ to branches |
| Inventory (HQ) | 4 | Stock levels at Kafrelsheikh HQ only |
| Expenses | 1,200 | Monthly expenses per branch |
| Debt & AR | 172 | Customer debts & collection status |
| Employee KPIs | 41 | Performance per employee |
| Employee Directory | 41 | Full staff list with contacts & IDs |
| Customer Master | 54 | All pharmacies & stores |
| Medicine Master | 4 | Product pricing & margins |
| Executive Summary | — | Top-level KPI dashboard |

---

##  Analysis Phases

###  Phase 1 — Where Are We Now?
- Total revenue: **EGP 6,221,667**
- Gross profit: **EGP 2,689,661**
- Profit margin: **43.23%**
- Revenue grew **8.89%** from 2023 to 2024
- Cairo fastest growing at **+20.32%**
- Mansoura declining at **-7.84%**

###  Phase 2 — Who Is Performing?
- **Top Medical Rep:** Mariam Salem (Gharbia — Tanta) — EGP 203,337 profit
- **Top Collector:** Reham Fouad (Kafrelsheikh) — 72.43% collection rate
- **Weakest Collector:** Hana Lotfy (Gharbia) — 48.73% collection rate
- **Best Medicine:** Atorvastatin 20mg — EGP 1,017,547 total profit

###  Phase 3 — Where Is the Money Leaking?
- Every branch is **over budget**
- Total overspend: **EGP 598,800+**
- Cairo Miscellaneous **17% over budget** — needs audit
- Outstanding debt: **EGP 1,000,327** uncollected
- Overall collection rate only **55.73%**

###  Phase 4 — Growth Opportunities
- **December** is best month every year
- **June & September** growing fast in 2024
- **May & February** consistently weakest — need promotions
- Atorvastatin & Vitamin D3 growing fastest in quantity

###  Phase 5 — Forecast 2025
- Expected Revenue: **EGP 3,531,455**
- Expected Gross Profit: **EGP 1,526,648**
- ** Warning:** Expenses projected at EGP 4,520,040 — action needed

###  Phase 6 — Recommendations
- Stop credit for high risk customers immediately
- Move top reps to high growth areas
- Audit Cairo miscellaneous expenses
- Target 75%+ collection rate
- Invest heavily in Cairo — growing 20%

---

##  Key Insights

| Insight | Finding |
|---|---|
| Best Governorate | Cairo — EGP 985,343 revenue in 2024 |
| Worst Governorate | Mansoura — declining -7.84% |
| Best Medicine | Atorvastatin — highest profit everywhere |
| Worst Medicine | Metformin — completely flat growth |
| Biggest Debt Risk | Talkha Medical Store — 12% collection rate |
| Best Rep | Mariam Salem — EGP 203,337 profit |
| Best Collector | Reham Fouad — 72.43% collection rate |
| Biggest Expense Leak | Salaries overspent in every branch |



##  Visualizations

| Chart | Description |
|---|---|
| 01_revenue_by_governorate | Revenue comparison 2023 vs 2024 per branch |
| 02_profit_by_medicine | Gross profit per medicine 2023 vs 2024 |
| 03_monthly_trend | Monthly revenue trend across both years |
| 04_top_reps | Top 10 medical reps by profit |
| 05_debt_analysis | Collected vs outstanding debt per branch |
| 06_forecast_2025 | Revenue forecast and growth rates for 2025 |
| 07_expense_analysis | Budget vs actual expenses analysis |
| 08_executive_dashboard | Full executive summary dashboard |

---

##  2025 Targets

| Metric | Target |
|---|---|
| Revenue | EGP 3,800,000+ |
| Gross Profit | EGP 1,642,000+ |
| Expenses | Under EGP 1,300,000 |
| Net Profit | EGP 342,000+ |
| Collection Rate | 75%+ |
| Cairo Revenue | EGP 1,400,000 |

---

##  Author

**[Ahmed Nasser]**
Data Analyst
ahmed.nasser01166@email.com
---

##  License

This project is for business analysis and internal use only.