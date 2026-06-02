# 📊 FP&A AI Skills — Free Excel Templates

**4 professional FP&A templates built with AI to automate the most time-consuming finance tasks.**

Built by an FP&A professional following the [AI reskilling playbook](https://twitter.com/clairevo) — replace manual work with intelligent, formula-driven models anyone can use.

> ⭐ If these templates save you time, please star this repo!

---

## 📁 Templates Included

### 1. 📈 Revenue Forecast — Rolling 12 Months
**`Revenue_Forecast_Rolling12M.xlsx`**

Automates monthly revenue forecasting using trend analysis and manual assumption overrides.

| Tab | What it does |
|-----|-------------|
| **Actuals** | 17 months of historical revenue by product line |
| **Assumptions** | Auto-calculates avg MoM growth from last 6 actuals. Override with your own rate (Y/N toggle) + seasonality index |
| **Forecast** | Rolling 12-month forecast — auto-compounds from assumptions |

**How to use:**
1. Replace blue cells in `Actuals` with your real monthly revenue
2. In `Assumptions`, review the auto-calculated trend or set `Use Override = Y` to enter your own growth rate
3. `Forecast` tab updates automatically

---

### 2. 💰 Annual Budget — Full P&L
**`Annual_Budget_FY2026.xlsx`**

Driver-based annual budget with monthly P&L, from Revenue down to Net Income.

| Tab | What it does |
|-----|-------------|
| **Assumptions** | Revenue growth %, margin targets (GM%, R&D, S&M, G&A), headcount by department |
| **Budget_PL** | Full monthly P&L: Revenue → COGS → Gross Profit → OPEX → EBITDA → Net Income |
| **Variance_Tracker** | Paste actuals each month → YTD Actual vs Budget + FY Forecast vs Budget auto-calculate |

**How to use:**
1. Enter your FY25 actuals and FY26 targets in `Assumptions` (yellow cells)
2. `Budget_PL` auto-populates all 12 months
3. Each month-end: set Current Month in `Variance_Tracker`, paste YTD actuals

---

### 3. 💲 Pricing Initiatives
**`Pricing_Initiatives_FY2026.xlsx`**

Models the revenue and P&L impact of pricing changes across products and scenarios.

| Tab | What it does |
|-----|-------------|
| **Pricing_Assumptions** | Current price/volume baseline → Proposed increases → Price elasticity model (volume impact auto-calculated) |
| **PVM_Bridge** | Price-Volume-Mix bridge: decomposes revenue variance into 3 effects |
| **Scenario_Analysis** | Conservative / Base / Aggressive pricing scenarios → full P&L impact |
| **Initiative_Tracker** | All initiatives with owner, status (🟢 Approved / 🟡 In Review / 🔵 Planned), revenue impact, risk level |

**How to use:**
1. Enter current prices and volumes in `Pricing_Assumptions` Section A
2. Enter proposed price changes and elasticity in Section B — volume impact auto-calculates
3. Review 3 scenarios in `Scenario_Analysis` and adjust GM%/OPEX% assumptions in row 14
4. Track approval status in `Initiative_Tracker`

**Price Elasticity quick guide:**
- `-0.2` → Enterprise SaaS (very sticky, minimal churn)
- `-0.5` → Mid-market software
- `-1.0` → SMB/online tools
- `-2.0` → Commoditized, price-sensitive market

---

### 4. 📉 Performance Drivers
**`Performance_Drivers_FY2026.xlsx`**

Tracks 16 KPIs monthly and decomposes EBITDA variance into root-cause drivers.

| Tab | What it does |
|-----|-------------|
| **KPI_Tracker** | 16 KPIs across Revenue, Margin, Cost, People & Customer — monthly actuals vs FY target. 5 rows auto-calculate from other inputs |
| **EBITDA_Bridge** | Step-by-step EBITDA decomposition: Volume + Price + Margin Rate + Mix + OPEX effects |
| **Driver_Analysis** | 5 drivers × 4 metrics: Volume, Price, Mix, Cost Efficiency, Productivity — vs Budget and vs PY |
| **Exec_Summary** | One-page scorecard with RAG status 🟢🔴 + narrative commentary per driver |

**How to use:**
1. Enter monthly actuals in yellow cells of `KPI_Tracker` — formula rows auto-calculate
2. Update `EBITDA_Bridge` inputs quarterly to explain YoY EBITDA change
3. Fill `Driver_Analysis` monthly for variance commentary
4. Use `Exec_Summary` for leadership/board reporting

---

## 🎨 Color Coding (Industry Standard)

All templates follow professional FP&A color conventions:

| Color | Meaning |
|-------|---------|
| 🔵 **Blue text** | Hardcoded inputs — replace with your data |
| 🟡 **Yellow background** | Key assumptions — your inputs |
| ⚫ **Black text** | Formulas — do not edit |
| 🟢 **Green text** | Cross-sheet links — do not edit |

---

## 🚀 Getting Started

1. **Download** any template from this repo
2. **Replace** blue/yellow cells with your company's data
3. **Everything recalculates** automatically — no VBA, no macros

---

## 🛠️ Built With

- Microsoft Excel (Office 365)
- Claude Code (AI-assisted development)
- PowerShell + Excel COM automation

---

## 👤 About

Built by an FP&A professional automating finance work with AI.

- 🔗 LinkedIn: [linkedin.com/in/elb1289](https://linkedin.com/in/elb1289)
- 📧 Contact: elb1289@gmail.com

---

## 📄 License

Free to use and adapt. If you improve a template, consider sharing back!

---

*Built following the [@clairevo](https://twitter.com/clairevo) AI reskilling playbook — "The gap in AI adoption is getting bigger. Start reskilling now while it's early."*
