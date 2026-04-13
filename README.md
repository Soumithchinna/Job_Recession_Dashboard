# 📉 Recession Jobs Dashboard

An Excel-based interactive dashboard analyzing the impact of economic recessions on employment, salaries, layoffs, and workforce trends across four countries and five industries.

---

## 📊 Overview

This workbook explores how recessions affect labor markets using a structured dataset of **200 records** spanning two major global downturns — the **2008–2009 Financial Crisis** and the **2020–2021 COVID-19 Recession**. It includes pre- and post-recession comparisons of job counts, salaries, layoffs, hiring rates, unemployment rates, and GDP growth.

---

## 🗂️ Workbook Structure

| Sheet | Description |
|---|---|
| `Recession Jobs Data` | Raw dataset — 200 rows, 14 columns |
| `Dashboard` | Summary overview dashboard |
| `Industry Dashboard` | Breakdown by industry |
| `Trends_dashboard` | Year-over-year trend analysis |
| `Workforce_dashboard` | Workforce-level metrics (hiring, layoffs) |
| `About` | Project description and notes |
| `pivot_tabels` | Pivot tables powering the dashboards |

---

## 🗃️ Dataset Columns

| Column | Description |
|---|---|
| `Year` | Recession year (2008, 2009, 2020, or 2021) |
| `Country` | Country of observation (USA, UK, Germany, India) |
| `Industry` | Sector (Healthcare, Retail, Finance, IT, Manufacturing) |
| `Company_Size` | Small, Medium, or Large |
| `Before_Jobs` | Number of jobs before the recession |
| `After_Jobs` | Number of jobs after the recession |
| `Job_Change_%` | Percentage change in jobs |
| `Before_Salary` | Average salary before the recession |
| `After_Salary` | Average salary after the recession |
| `Salary_Change_%` | Percentage change in salary |
| `Unemployment_Rate` | Unemployment rate (%) during the period |
| `GDP_Growth` | GDP growth rate (%) during the period |
| `Layoffs` | Number of layoffs recorded |
| `Hiring_Rate` | Hiring rate during the period |

---

## 🔍 Key Findings

### Overall Impact
- Jobs declined by an average of **~13.9%** across all observations
- Salaries fell by an average of **~9.6%**
- Total layoffs across all records: **28,435**
- Average unemployment rate: **~7.9%**
- Average GDP growth: **-1.04%** (contractionary in both downturns)

### By Country
| Country | Avg Job Change | Avg Unemployment Rate |
|---|---|---|
| Germany | -16.1% | 7.6% |
| UK | -14.0% | 8.0% |
| USA | -12.7% | 8.1% |
| India | -12.7% | 7.7% |

Germany experienced the steepest job losses on average, while India and the USA showed comparatively more resilience.

### By Industry
| Industry | Avg Job Change | Avg Layoffs |
|---|---|---|
| Healthcare | -16.2% | 149 |
| Finance | -15.6% | 119 |
| Retail | -14.9% | 146 |
| Manufacturing | -12.0% | 160 |
| IT | -11.4% | 142 |

Despite being an essential sector, **Healthcare** saw the steepest proportional job losses. **IT** was the most resilient. **Manufacturing** recorded the highest average layoff count.

### By Company Size
| Size | Avg Job Change |
|---|---|
| Large | -17.0% |
| Medium | -11.6% |
| Small | -12.7% |

Large companies cut the most jobs proportionally, likely reflecting greater workforce restructuring capacity during downturns.

### By Recession Period
| Year | Avg Job Change | Avg GDP Growth |
|---|---|---|
| 2008 | -14.1% | -1.29% |
| 2009 | -15.5% | -1.14% |
| 2020 | -11.5% | -0.88% |
| 2021 | -14.6% | -0.93% |

The **2008–2009 Financial Crisis** caused sharper job losses than the **2020–2021 COVID period** on a per-record basis, though layoff volumes were higher in 2020–2021.

---

## 🛠️ Requirements

- **Microsoft Excel** 2016 or later (for slicers and pivot tables to function correctly)
- Alternatively, **LibreOffice Calc** can open the file, but some dashboard formatting and slicer interactivity may not render fully

---

## 🚀 Getting Started

1. Clone or download this repository
2. Open `recession_jobs_dashboard.xlsx` in Excel
3. Navigate to any dashboard sheet (`Dashboard`, `Industry Dashboard`, etc.)
4. Use the slicers/filters to explore data by country, industry, year, or company size

---

## 📌 Notes

- `Job_Change_%` and `Salary_Change_%` are computed via Excel formulas (`=(After-Before)/Before`) in the raw data sheet
- The dataset covers four specific recession years and is not a continuous time series
- All salary figures are in local currency units as-is (no normalization for purchasing power parity)

---

## 📄 License

This project is for educational and analytical purposes. Feel free to fork, adapt, or build upon it with attribution.
