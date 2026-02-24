# 📊 Automated Sales Reporting System

An end-to-end automated sales reporting pipeline built with Python. Loads raw retail data, cleans it, computes key business KPIs, generates visualizations, and exports a professional multi-sheet Excel report — all from a single Jupyter Notebook.

---

## 📥 How to Download

All project files are available directly in this repository. Click on any file and hit the **Download** button to save it locally.

| File | Description |
|------|-------------|
| `train.csv` | Raw Superstore Sales Dataset (9,800 rows) |
| `automated-sales-reporting.ipynb` | Full Python Notebook — complete pipeline |
| `sales_report.xlsx` | Excel Report — 5 sheets + embedded charts |

---

## 📊 Dataset

- **Source:** Superstore Sales (Kaggle)
- **Size:** 9,800 rows × 18 columns
- **Date Range:** January 2015 – December 2018

---

## 🔑 Key KPIs

| Metric | Value |
|--------|-------|
| 💰 Total Sales | $2,261,536.78 |
| 📦 Total Unique Orders | 4,922 |
| 📊 Average Sale | $230.77 |
| 🏆 Top Region | West — $710,219 (31%) |
| 🛒 Top Category | Technology — $827,455 |
| 📅 Best Month | November 2018 — $117,938 |
| 📆 Best Year | 2018 — $722,052 |

---

## 💡 Key Insights

- **West region leads** with 31% of total revenue
- **Technology** is the top-performing category across all years
- **November peaks every year** — strong holiday/seasonal effect
- **2016 saw a sales dip** vs 2015 — worth investigating
- Clear **year-over-year growth** from 2016 → 2018

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| `pandas` | Data loading, cleaning, GroupBy analysis |
| `matplotlib` | Chart generation |
| `openpyxl` | Excel export with embedded charts |
| `Jupyter Notebook` | Interactive development |

---

## ⚙️ How to Run

Install the required libraries, then open `automated-sales-reporting.ipynb` in Jupyter and click **Kernel → Restart & Run All**.
```bash
pip install pandas matplotlib openpyxl jupyter
```

---

## 📤 Output — `sales_report.xlsx`

The Excel report contains 5 sheets, each with an embedded chart:

- **Raw Data** — all 9,800 rows of cleaned data
- **Region Summary** — sales totals by region
- **Category Summary** — sales totals by category
- **Monthly Summary** — month-by-month sales trend
- **Yearly Summary** — year-by-year sales totals

---

## 🤝 Skills Demonstrated

- Data wrangling — null handling, type conversion, datetime parsing
- KPI extraction via aggregation
- Multi-panel data visualization
- Automated Excel reporting with embedded charts
- Clean, reproducible Jupyter Notebook workflow

---

