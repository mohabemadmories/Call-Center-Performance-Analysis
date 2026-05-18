# 📞 Call Center Performance Analysis — MIS Case Study
### Power BI · DAX · Business Intelligence · Operational Analytics

---

## 📌 Project Overview

A full operational analysis of a **Bosch call center** spanning Denmark, Finland, Norway, and Sweden. The project consists of **3 interactive Power BI dashboards** that dissect call performance, agent efficiency, and hourly abandonment patterns — translating raw call logs into executive-ready insights and actionable staffing recommendations.

---

## 🗂️ Dashboards

### 1. 📊 Call Performance Dashboard
Tracks monthly trends in Hold Time, Post-Call Work (ACW), and Average Handling Time (AHT) across services and countries.

**Key Findings:**
- 🔴 **Hold Time Peak:** A significant spike in Hold Duration was detected in **April 2025**, reaching ~20K seconds — indicating potential staffing shortages or system-level issues
- 📈 **Wrap-up Increase:** ACW rose sharply in **May 2025**, directly contributing to an overall increase in AHT
- ⏱️ **AHT Growth:** Average Handling Time increased steadily from **3.7 to 3.95 minutes** between January and May 2025

**Filters Available:** Service type, Country, Language

---

### 2. 👤 Agent Performance Dashboard
An individual-level scorecard measuring Case Share, AHT, Occupancy, Adherence (ADH%), Lost Hours, and Schedule Conformance.

**Key Findings:**
- ⚠️ **Performance Gaps:** AHT outliers as high as **20.13 minutes** vs. a team average of **6.01 minutes** — flagging critical candidates for quality coaching
- 🕳️ **Operational Leakage:** **2,882 total Lost Hours** detected; individual agents logged over **200 lost hours each**, suggesting payroll or system logging errors
- 📉 **Underutilization:** Team occupancy sits at **30.5%**, indicating significant idle time and potential overstaffing relative to call volume
- 🏆 **Benchmark Standards:** Top performers achieving **100% Conformance** and **100% ADH** identified as internal benchmarks

**Filters Available:** Date range, Shift Type (Day/Night), Team Leader

---

### 3. 🕐 Hourly Abandonment Heat Map
A granular heat map showing abandonment rates by hour-of-day across all 23 days of the reporting period.

**Key Findings:**
- 🚨 **7:00 PM – 7:30 PM Critical Gap:** Consistent **100% abandonment rate** at end-of-shift — zero staffing coverage during final shift hour
- 🌅 **Morning Rush (8:00 – 10:00 AM):** Abandonment fluctuates between **40% and 60%** — current shift start times don't match early call volume demand
- 📅 **Day 20 Outlier:** An unusual spike across nearly all hours on Day 20 — likely an operational incident or system downtime requiring investigation
- ✅ **Optimal Window:** **10:30 AM – 12:30 PM** is the most stable period, where staffing levels effectively meet call demand

---

## 🛠️ Technical Stack

| Tool | Usage |
|------|-------|
| **Power BI Desktop** | Dashboard design, interactive visuals, cross-filtering |
| **DAX** | Custom measures, time-based transformations, KPI calculations |
| **Data Source** | Call center operational logs (Bosch — Nordics region) |

---

## 💡 Business Impact

| Insight | Recommended Action |
|--------|-------------------|
| 100% abandonment at 7:00–7:30 PM | Extend shift coverage by 30 minutes or add evening rotation |
| 2,882 Lost Hours detected | Audit payroll system; flag agents with 200+ lost hours for review |
| AHT rising from 3.7 → 3.95 min | Investigate ACW root cause; consider post-call workflow automation |
| 30.5% team occupancy | Review staffing model against actual call volume patterns |
| Morning abandonment 40–60% | Shift start time adjustment or add pre-8:30 AM coverage |

---

## 📁 Repository Structure

```
📦 Call-Center-MIS-CaseStudy
 ┣ 📊 Call Performance.pbix          # Monthly AHT, Hold Time & ACW trends
 ┣ 📊 Agent Performance.pbix         # Individual agent KPI scorecard
 ┣ 📊 Hourly_Call Center Performance.pbix  # Hourly abandonment heat map
 ┣ 📄 Call_Performance.pdf           # Dashboard export — Call Performance
 ┣ 📄 Agent_performance.pdf          # Dashboard export — Agent Performance
 ┣ 📄 Hourly Call Center Performance.pdf  # Dashboard export — Hourly Heat Map
 ┗ 📄 README.md
```

---

## 🚀 How to Use

1. Download the `.pbix` files
2. Open with **Power BI Desktop** (free download at [powerbi.microsoft.com](https://powerbi.microsoft.com))
3. Use the slicers (Date, Country, Service, Shift Type, Team Leader) to explore the data interactively
4. PDF exports are available for quick viewing without Power BI

---

## 👤 Author

**Mohab Emad** — Data Analyst & Business Analyst
- 🔗 [LinkedIn](https://www.linkedin.com/in/mohabemad/)
- 🐙 [GitHub](https://github.com/mohabemadmories)
- 📧 mohabemadmorris@gmail.com
