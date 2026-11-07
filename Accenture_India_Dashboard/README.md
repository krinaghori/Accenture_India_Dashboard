<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=A100FF&center=true&vCenter=true&width=720&lines=Filter+%7C+Explore+%7C+Visualize+%7C+Decide;50%2C000+Employees+%C2%B7+5+Dashboards+%C2%B7+1+HR+Story;Built+in+Power+BI+%F0%9F%93%8A" alt="Typing SVG" />

<br/>

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-7500C0?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-HR_Analytics-A100FF?style=for-the-badge)
![Employees](https://img.shields.io/badge/Employees-50%2C000-22C55E?style=for-the-badge)
![Pages](https://img.shields.io/badge/Report_Pages-5-F97316?style=for-the-badge)
![Visuals](https://img.shields.io/badge/Data_Visuals-53-0EA5E9?style=for-the-badge)
![Maps](https://img.shields.io/badge/Maps-5-EC4899?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-10B981?style=for-the-badge)

<br/>

[![Watch the Presentation](https://img.shields.io/badge/%E2%96%B6_Watch_the_Presentation-EF4444?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/19MctFShKcMRnU8JcZxusgGeFE_fkEH_N/view?usp=drive_link)
[![Dashboard Preview](https://img.shields.io/badge/%F0%9F%96%BC_Dashboard_Preview-7500C0?style=for-the-badge)](#-dashboard-preview)
[![Key Insights](https://img.shields.io/badge/%F0%9F%8F%86_Key_Insights-F59E0B?style=for-the-badge)](#-results--insights)
[![How to Open](https://img.shields.io/badge/%E2%96%B6_How_to_Open-10B981?style=for-the-badge)](#-how-to-open--use)

<br/>

> 🚀 A **5-page Power BI report** for **Accenture India** that turns **workforce, attrition, compensation, performance and hiring data for 50,000 employees** into interactive dashboards — 23 KPI cards, 20 charts, 5 maps and 5 drill-down tables, all filtered by Year, Department, Location, Job Level and Gender — **data as on 30 Apr 2025**.

</div>

---

## 📑 Table of Contents

1. [Overview](#-overview)
2. [Problem Statement](#-problem-statement)
3. [Features](#-features)
4. [Key Features](#-key-features)
5. [Project Structure](#-project-structure)
6. [Dashboard Layout](#-dashboard-layout)
7. [Data Preparation & Modelling](#-data-preparation--modelling)
8. [Data Model & Fields](#-data-model--fields)
9. [Panel 1 — KPI Cards](#-panel-1--kpi-cards)
10. [Panel 2 — Filters](#-panel-2--filters)
11. [Panel 3 — Workforce Overview](#-panel-3--workforce-overview)
12. [Panel 4 — Attrition & Retention](#-panel-4--attrition--retention)
13. [Panel 5 — Compensation Analytics](#-panel-5--compensation-analytics)
14. [Panel 6 — Performance & Promotion](#-panel-6--performance--promotion)
15. [Panel 7 — Executive Summary](#-panel-7--executive-summary)
16. [Tech Stack](#-tech-stack)
17. [Results & Insights](#-results--insights)
18. [Advantages](#-advantages)
19. [How to Open & Use](#-how-to-open--use)
20. [Project Presentation](#-project-presentation)
21. [Dashboard Preview](#-dashboard-preview)
22. [License](#-license)
23. [Author](#-author)
24. [Acknowledgements](#-acknowledgements)

---

## 🔭 Overview

**Accenture India HR Dashboard** is a 5-page `.pbix` report that gives HR leaders one place to see **who works at the company, who leaves, what they earn, how they perform and how the hiring funnel converts** — **data as on 30 Apr 2025**. A dark-purple sidebar holds the page navigation (*Workforce Overview*, *Attrition & Retention*, *Compensation Analytics*, *Performance & Promotion*, *Executive Summary*), a row of slicers and a **Filter** button sit at the top of each page, and the main canvas shows headline KPI cards followed by bar, column, line, donut, treemap, scatter and funnel charts, a map and a drill-down table.

Every visual is **live and connected** to one data model — choose a Department, Location or Gender and the cards, charts and tables update together. All figures come from **DAX measures** kept in a single `Measure Table`.

<div align="center">

| 👥 **50,000** | ⚠️ **16.00%** | 💰 **33.06 LPA** | ⭐ **3.58** | 🎓 **92.01%** |
|:---:|:---:|:---:|:---:|:---:|
| Total Employees | Attrition Rate | Average Salary | Avg Performance Rating | Training Completion |

</div>

---

## ❗ Problem Statement

Employee records, exit logs, payroll, appraisal and training data usually sit in separate files, so HR teams struggle to answer questions such as:

- 👥 How big is the workforce, and how is it spread across departments, locations and gender?
- ⚠️ How many employees are leaving, who is leaving, and how long did they stay?
- 💰 What is the payroll and the average, median and highest salary — by department, job level and location?
- ⭐ How are employees performing, who gets promoted, and are trainings being completed?
- 🧭 How healthy is each department when attrition, rating, salary, promotion and training are viewed together?
- 🪜 How many applicants turn into joiners, and how many are retained?

**Accenture India HR Dashboard** answers all of these across **five interactive pages**.

---

## ✨ Features

| Feature | Visual | Description |
|---|---|---|
| 👥 **Total & Active Employees** | Cards | Headcount with previous-year comparison |
| ⚠️ **Attrition & Retention Rate** | Cards | Attrition % and retention % against previous year |
| 🧬 **Gender Ratio** | Card | Male : Female split of the workforce |
| 📅 **Avg Tenure / Avg Exit Tenure** | Cards | Years of service for current and exiting employees |
| 💰 **Total Payroll** | Card | Payroll in ₹ Cr |
| 💵 **Average / Median / Highest Salary** | Cards | Salary KPIs in LPA |
| ⭐ **Avg Performance Rating** | Card | Mean rating on a 1–5 scale |
| 🚀 **Promotion Rate & High Performers** | Cards | Share promoted and count of top performers |
| 🎓 **Training Completion %** | Card | Share of trainings completed |
| 🎛️ **Filters** | Slicers + Filter button | Year, Quarter, Department, Business Unit, Location, Job Level / Role, Gender |
| 📊 **Employees by Department** | Clustered Column Chart | Headcount per department |
| 🗺️ **Maps (5)** | Map | Employees, attritions, salary and high performers by city |
| 🍩 **Workforce Composition** | Donut Chart | Male vs Female employees |
| 📈 **Hiring Trend** | Line Chart | Drill down Year → Quarter → Month |
| 📉 **Attrition Charts** | Bar, Column, Line, Donut, Treemap | By department, age group, trend, gender and high-risk segment |
| 💎 **Salary Charts** | Column, Bar, Scatter, Donut | By salary band, department, job level, experience and gender |
| 🚀 **Promotion Charts** | Bar, Donut, Line | Promotions by department, training status and monthly trend |
| 🪜 **Employee Lifecycle Funnel** | Funnel Chart | Applicant → Interview → Offer → Joined → Retained |
| 🎯 **Attrition % vs Average Salary** | Scatter Chart | Department-level comparison with a reference line |
| 🧮 **Drill-down Tables (5)** | Matrix / Table | Business unit, department, job level and team summaries |
| 🩺 **Department Health Scorecard** | Table with icons | Attrition, rating, salary, health score, promotion and training |

---

## 🌟 Key Features

| Feature | Description |
|---|---|
| 🔗 **One Connected Model** | Dimension and fact tables are linked, so filters apply consistently across all five pages |
| 🧮 **DAX Measures** | Attrition %, retention %, tenure, payroll, promotion rate and more live in one `Measure Table` |
| 🧭 **Drill-down Hierarchies** | Business Unit → Department, Department → Team, Department → Job Level and Year → Quarter → Month |
| 🆚 **Previous-Year Comparison** | Almost every KPI card shows `vs PY` with an up / down arrow and % change |
| 🗺️ **Map Views** | Employees, attritions, salary and high performers plotted by city |
| 🪜 **Hiring Funnel** | A funnel from 48,560 applicants down to 5,620 retained employees |
| 🩺 **Health Scorecard** | Icon-based scorecard that ranks departments on a single health score |
| 🎨 **Branded Design** | Accenture purple theme, icon cards, taglines and a faint building watermark in the sidebar |
| 🖼️ **Fit-to-Page Canvas** | Designed to scale across screen sizes |
| ♻️ **Native Visuals Only** | Card, Column, Bar, Line, Donut, Treemap, Scatter, Funnel, Map, Matrix and Table |

---

## 📁 Project Structure

```
📦 Accenture-HR-Dashboard/
 ┣ 📄 README.md                                      ← Project documentation (you're here!)
 ┣ 📊 Accenture_Dashboard.pbix                       ← Power BI report (5 pages)
 ┣ 🖼️ Page_1_-_Workforce_Overview_1.png              ← Page 1 screenshot
 ┣ 🖼️ Page_2_-_Attrition___Retention_1.png           ← Page 2 screenshot
 ┣ 🖼️ Page_3_-_Compensation_Analytics_1.png          ← Page 3 screenshot
 ┣ 🖼️ Page_4_-_Performance___Promotion_1.png         ← Page 4 screenshot
 ┣ 🖼️ Page_5_-_Executive_Summary_1.png               ← Page 5 screenshot
 ┗ 📁 assets/
    ┗ 🎞️ video_thumbnail.png                         ← Clickable presentation thumbnail
```

> 🎬 The **project presentation** is hosted on **Google Drive** — [watch it here](https://drive.google.com/file/d/19MctFShKcMRnU8JcZxusgGeFE_fkEH_N/view?usp=drive_link).

---

## 🖥️ Dashboard Layout

Every page shares one frame: **sidebar navigation on the left, slicers and a Filter button on top, KPI cards, then charts and a table.**

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  ACCENTURE       │ Year │ Quarter │ Department │ Business Unit │ Location │ Job Level │ Gender │ Filter │
│                  │┌──────────┬──────────┬──────────┬──────────┬──────────────┐│
│ > Workforce      ││ Total    │ Active   │ Attrition│ Avg      │ Gender Ratio ││
│   Overview       ││ Employees│ Employees│ Rate %   │ Tenure   │              ││
│                  │└──────────┴──────────┴──────────┴──────────┴──────────────┘│
│   Attrition &    │┌───────────────────────┬────────────────┬──────────────────┐│
│   Retention      ││ Employees by          │ Employees by   │ Workforce        ││
│                  ││ Department (column)   │ Location (map) │ Composition      ││
│   Compensation   ││                       │                │ (donut)          ││
│   Analytics      ││                       │                ├──────────────────┤│
│                  ││                       │                │ Hiring Trend     ││
│   Performance &  │└───────────────────────┴────────────────┴──────────────────┘│
│   Promotion      │┌──────────────────────────────────────────┬────────────────┐│
│                  ││ Workforce Summary by Business Unit and   │ Key Insights   ││
│   Executive      ││ Department (matrix, drill-down)          │                ││
│   Summary        │└──────────────────────────────────────────┴────────────────┘│
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 1 — Workforce Overview
```

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  ACCENTURE       │ Year │ Department │ Location │ Job Role │ Gender │ Filter │
│                  │┌──────────┬──────────┬──────────┬──────────────────────────┐│
│   Workforce      ││ Total    │ Attrition│ Retention│ Avg Exit Tenure          ││
│   Overview       ││ Attritions│ Rate %  │ Rate %   │                          ││
│                  │└──────────┴──────────┴──────────┴──────────────────────────┘│
│ > Attrition &    │┌───────────────────┬─────────────────┬────────────────────┐│
│   Retention      ││ Attrition by      │ Attrition by    │ Attrition Trend    ││
│                  ││ Department (bar)  │ Age Group (col) │ (line, drill)      ││
│   Compensation   │├──────────┬────────┴─────────┬───────┴────────────────────┤│
│   Analytics      ││ By Gender│ Attrition by     │ Attrition Details by       ││
│                  ││ (donut)  │ Location (map)   │ Department (table)         ││
│   Performance &  ││ High-Risk│                  │                            ││
│   Promotion      ││ (treemap)│                  │                            ││
│   Executive      │└──────────┴──────────────────┴────────────────────────────┘│
│   Summary        │ Key Insights                                                │
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 2 — Attrition & Retention
```

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  ACCENTURE       │ Department │ Job Role │ Gender │ Location │ Filter         │
│                  │┌─────────┬──────────┬──────────┬──────────┬───────────────┐│
│   Workforce      ││ Total   │ Average  │ Highest  │ Median   │ Employees     ││
│   Overview       ││ Payroll │ Salary   │ Salary   │ Salary   │ Covered PY    ││
│                  │└─────────┴──────────┴──────────┴──────────┴───────────────┘│
│   Attrition &    │┌─────────────────┬──────────────────┬─────────────────────┐│
│   Retention      ││ Salary          │ Avg Salary by    │ Avg Salary by       ││
│                  ││ Distribution    │ Department (bar) │ Job Level (column)  ││
│ > Compensation   │├─────────────────┼──────────────────┼─────────────────────┤│
│   Analytics      ││ Salary vs       │ Salary by        │ Salary by Gender    ││
│                  ││ Experience      │ Location (map)   │ (donut)             ││
│   Performance &  │└─────────────────┴──────────────────┴─────────────────────┘│
│   Promotion      │ Compensation Summary by Department and Job Level │ Insights │
│   Executive      │                                                             │
│   Summary        │                                                             │
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 3 — Compensation & Salary Analytics
```

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  ACCENTURE       │ Department │ Business Unit │ Gender │ Location │ Filter    │
│                  │┌───────────┬───────────┬───────────┬────────────────────┐ │
│   Workforce      ││ Avg Perf. │ Promotion │ High      │ Training           │ │
│   Overview       ││ Rating    │ Rate %    │ Performers│ Completion %       │ │
│                  │└───────────┴───────────┴───────────┴────────────────────┘ │
│   Attrition &    │┌─────────────┬───────────────┬──────────────┬────────────┐│
│   Retention      ││ Rating      │ Promotions by │ Promotions   │ Performers ││
│                  ││ Distribution│ Dept (bar)    │ Status(donut)│ by Location││
│   Compensation   │├─────────────┴───────────────┴──────────────┤ (map)      ││
│   Analytics      ││ Promotion Trend by Month (line)            │            ││
│                  │└────────────────────────────────────────────┴────────────┘│
│ > Performance &  │ Talent Scorecard (Department > Team)        │ Key Insights │
│   Promotion      │                                                             │
│   Executive      │                                                             │
│   Summary        │                                                             │
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 4 — Performance & Promotion
```

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  ACCENTURE       │┌─────────┬──────────┬──────────┬───────────┬──────────────┐│
│                  ││ Total   │ Avg      │ Attrition│ Promotion │ High         ││
│   Workforce      ││ Employees│ Salary  │ Rate %   │ Rate %    │ Performers   ││
│   Overview       │└─────────┴──────────┴──────────┴───────────┴──────────────┘│
│                  │┌───────────────┬──────────────────┬────────────────────────┐│
│   Attrition &    ││ Employee      │ Workforce Cost   │ Attrition % vs         ││
│   Retention      ││ Lifecycle     │ by Department    │ Average Salary         ││
│                  ││ Funnel        │ (treemap)        │ (scatter)              ││
│   Compensation   │├───────────────┴──────────────────┼────────────────────────┤│
│   Analytics      ││ Employee Distribution (map)      │ Department Health      ││
│                  ││                                  │ Scorecard (table)      ││
│   Performance &  │└──────────────────────────────────┴────────────────────────┘│
│   Promotion      │ Key Insights                                                │
│                  │                                                             │
│ > Executive      │                                                             │
│   Summary        │                                                             │
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 5 — Executive HR Summary
```

---

## 🧪 Data Preparation & Modelling

The report is built on a **star-style model** of dimension, fact and summary tables, with every calculation stored as a DAX measure.

| # | Step | What it does |
|:---:|---|---|
| 1️⃣ | **Load source tables** | Employee, department, location, job level, date, attrition, compensation, performance and training data are loaded into Power BI |
| 2️⃣ | **Build dimensions** | `DimEmployee`, `DimDepartment`, `DimLocation`, `DimJobLevel` and `DimDate` |
| 3️⃣ | **Build fact tables** | `FactWorkforce`, `FactAttrition`, `FactCompensation`, `FactPerformance` and `FactTraining` |
| 4️⃣ | **Add summary tables** | `PromotionTrend`, `LifecycleFunnel` and `DeptHealthScorecard` feed the trend, funnel and scorecard visuals |
| 5️⃣ | **Create relationships** | Dimensions are linked to the fact tables so slicers filter every page |
| 6️⃣ | **Add hierarchies** | Business Unit → Department, Department → Team / Job Level and Year → Quarter → Month |
| 7️⃣ | **Create `Measure Table`** | One table that holds all DAX measures (headcount, attrition, salary, performance, training) |
| 8️⃣ | **Design the pages** | Purple sidebar, icon cards, slicers, a Filter button and Key Insights on each page |

---

## 📋 Data Model & Fields

**📌 Dashboard at a glance**

| Metric | Value |
|---|---|
| 📄 Report pages | **5** |
| 📊 Data visuals | **53** (23 cards, 20 charts, 5 maps, 5 tables/matrices) |
| 👥 Employees | **50,000** (42,000 active) |
| 📆 Data as on | **30 Apr 2025** |
| 🏢 Departments | AI & ML · Analytics · Cloud · Consulting · Cyber Security · Data Science · Finance · HR · Legal · Marketing · Operations · PMO · SAP · Strategy · Technology |
| 📍 Cities | Ahmedabad · Bengaluru · Chennai · Gurugram · Hyderabad · Indore · Jaipur · Kochi · Kolkata · Mumbai · Noida · Pune |

**📌 Tables in the model**

| Table | Role |
|---|---|
| 👤 `DimEmployee` | Employee details such as `Gender` |
| 🏢 `DimDepartment` | `DepartmentName`, `Business Unit` |
| 📍 `DimLocation` | `City` |
| 🪜 `DimJobLevel` | `JobLevel` |
| 📅 `DimDate` | `Year`, `Quarter`, `Month` |
| 🧾 `FactWorkforce` | Workforce records |
| ⚠️ `FactAttrition` | Exits, `Age Group` |
| 💰 `FactCompensation` | `Salary Band`, `TotalSalaryLPA`, `YearsExperience` |
| ⭐ `FactPerformance` | `PerformanceRating` |
| 🎓 `FactTraining` | `Training Status`, `Team` |
| 📈 `PromotionTrend` | Monthly promotions |
| 🪜 `LifecycleFunnel` | `Stage`, `Headcount` |
| 🩺 `DeptHealthScorecard` | Attrition, rating, salary, health score, promotion and training by department |
| 🧮 `Measure Table` | All DAX measures |

**📌 Measures used on the dashboard**

| Page | Measures |
|---|---|
| 🟪 Workforce Overview | `Total Employees` · `Active Employees` · `Attrition Rate %` · `Avg Tenure Years` · `Gender Ratio` · `New Hires` · `Avg Experience (Years)` · `Avg Salary (₹ LPA)` · `Total Employees YoY %` |
| 🟣 Attrition & Retention | `Total Attritions` · `Retention Rate %` · `Avg Exit Tenure (Years)` · `vs PY Attrition Rate %` |
| 💜 Compensation | `Total Payroll` · `Average Salary` · `Highest Salary (LPA)` · `Median Salary (LPA)` · `Min Salary (LPA)` · `Employees` · `Employees Covered PY` |
| 🔮 Performance & Promotion | `Avg Performance Rating` · `Promotion Rate %` · `Promotions Count` · `Dept Promotions` · `High Performers` · `High Performer %` · `Training Completion %` |
| 🟪 Executive Summary | `Payroll PY (₹ Cr)` plus the headline measures above |

---

## 💰 Panel 1 — KPI Cards

> **Twenty-three native Card visuals** — four or five on each page, most with a previous-year comparison and a % change.

| Page | Card | Shown on dashboard | Previous year | Change |
|---|---|---|---|---|
| 🟪 Workforce | 👥 Total Employees | **50,000** | 46,567 | 🟢 +11.67% |
| 🟪 Workforce | 🧑‍💼 Active Employees | **42,000** | 40,102 | 🟢 +11.49% |
| 🟪 Workforce | ⚠️ Attrition Rate % | **16.00%** | 12.00% | 🔺 +4.00% |
| 🟪 Workforce | 📅 Avg Tenure Years | **4.80 Years** | 4.3 years | 🟢 +0.5 |
| 🟪 Workforce | ⚧ Gender Ratio | **61 : 39** (Male : Female) | — | — |
| 🟣 Attrition | 🚪 Total Attritions | **8,000** | 8,120 | 🔺 13.68% |
| 🟣 Attrition | ⚠️ Attrition Rate % | **16.00%** | 9.8% | 🔺 +1.6 |
| 🟣 Attrition | 🤝 Retention Rate % | **84.00%** | 89.2% | 🔻 −1.6% |
| 🟣 Attrition | ⏳ Avg Exit Tenure | **2.7 Years** | 2.9 years | 🔻 −0.2 |
| 💜 Compensation | 💼 Total Payroll | **16,530 Cr** | 15,240 Cr | 🟢 +12.35% |
| 💜 Compensation | 💵 Average Salary | **33.06 LPA** | 30.78 LPA | 🟢 +12.50% |
| 💜 Compensation | 🏆 Highest Salary | **62.74 LPA** | 79.67 LPA | 🟢 +10.64% |
| 💜 Compensation | 📊 Median Salary | **33.01 LPA** | 29.45 LPA | 🟢 +13.51% |
| 💜 Compensation | 👥 Employees Covered PY | **11,230** | 11,230 | 🟢 +11.67% |
| 🔮 Performance | ⭐ Avg Performance Rating | **3.58** | 3.4 | 🟢 +0.1% |
| 🔮 Performance | 🚀 Promotion Rate % | **26.81%** | 25.68% | 🟢 +1.0% |
| 🔮 Performance | 🏅 High Performers | **27,223** | 25,890 | 🟢 +7.89% |
| 🔮 Performance | 🎓 Training Completion % | **92.01%** | 90.45% | 🟢 +9.00% |
| 🟦 Executive | 👥 Total Employees | **50,000** | 46,567 | 🟢 +11.67% |
| 🟦 Executive | 💵 Avg Salary (₹ LPA) | **26 LPA** | 24.89 LPA | 🟢 +11.49% |
| 🟦 Executive | ⚠️ Attrition Rate % | **16.00%** | 12.00% | 🔺 +4.00% |
| 🟦 Executive | 🚀 Promotion Rate % | **26.81%** | 23.56% | 🟢 +11.34% |
| 🟦 Executive | 🏅 High Performers | **27,223** | — | — |

> [!TIP]
> ✅ **Reading it:** headcount grew **11.67%** to **50,000**, but **attrition rose from 12.00% to 16.00%** — the one KPI on the Workforce page that moved the wrong way.

---

## 🎛️ Panel 2 — Filters

> **Slicers** at the top of each page plus a purple **Filter** button.

| Page | Slicers |
|---|---|
| 🟪 Workforce Overview | Year · Quarter · Department · Business Unit · Location · JobLevel · Gender |
| 🟣 Attrition & Retention | Year · Department · Location · Job Role · Gender |
| 💜 Compensation Analytics | Department · Job Role · Gender · Location |
| 🔮 Performance & Promotion | Department · Business Unit · Gender · Location |
| 🟦 Executive Summary | No slicers — a strategic, fixed view |

| Slicer Field | Table |
|---|---|
| 📆 `Year` · 🗓️ `Quarter` | `DimDate` |
| 🏢 `DepartmentName` · `Business Unit` | `DimDepartment` |
| 📍 `City` | `DimLocation` |
| 🪜 `JobLevel` (shown as Job Role on some pages) | `DimJobLevel` |
| ⚧ `Gender` | `DimEmployee` |

---

## 🟪 Panel 3 — Workforce Overview

> **Page 1** — a Column Chart, a Map, a Donut Chart, a Line Chart and a drill-down Matrix.

| Visual | Type | Field Roles |
|---|---|---|
| 📊 Employee Distribution by Department | Clustered Column | Axis `DepartmentName` · Values `Total Employees` |
| 🗺️ Employee Distribution by Location | Map | Location `City` · Size `Total Employees` |
| 🍩 Workforce Composition | Donut (centre: **27,062**) | Legend `Gender` · Values `Total Employees` |
| 📈 Hiring Trend | Line Chart (Year > Quarter > Month) | Axis `Year`, `Quarter`, `Month` · Values `New Hires`, `Total Employees` |
| 🧮 Workforce Summary | Matrix (Business Unit > Department) | `Attrition Rate %`, `Avg Salary`, `Avg Experience`, `Total Employees`, `Total Employees YoY %` |

**📊 Employees by department**

| Department | Employees | Visual |
|---|---|---|
| 🥇 SAP | 3,477 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🥈 PMO | 3,417 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🥉 Data Science | 3,411 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 4️⃣ Legal | 3,399 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 5️⃣ AI & ML | 3,374 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 6️⃣ HR | 3,343 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 7️⃣ Cloud | 3,323 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 8️⃣ Finance | 3,318 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |

**🍩 Workforce composition** — 👨 Male **16,418 (60.67%)** · 👩 Female **10,644 (39.3%)**

**🧮 Workforce Summary — Support Functions**

| Department | Attrition Rate % | Avg Salary | Avg Experience (Years) | Total Employees |
|---|---|---|---|---|
| **Support Functions** | 16.25% | 27 LPA | 4.80 | 27,062 |
| ↳ AI & ML | 16.69% | 26 LPA | 4.80 | 3,374 |
| ↳ Cloud | 15.56% | 26 LPA | 4.80 | 3,323 |
| ↳ Data Science | 16.71% | 26 LPA | 4.80 | 3,411 |
| ↳ Finance | 16.76% | 27 LPA | 4.50 | 3,318 |
| ↳ HR | 15.70% | 26 LPA | 4.20 | 3,343 |
| 🏁 **Total** | **16.25%** | **27 LPA** | **4.80** | **27,062** |

> [!TIP]
> ✅ **Reading it:** the eight departments shown are almost the same size (**3,318–3,477** employees each). **Bengaluru** has the biggest employee base (**3,020**), then **Hyderabad** (1,920) and **Mumbai** (1,680).

---

## 🟣 Panel 4 — Attrition & Retention

> **Page 2** — a Bar Chart, a Column Chart, a Line Chart, a Donut, a Map, a Treemap and a Table.

| Visual | Type | Field Roles |
|---|---|---|
| 📉 Attrition by Department | Clustered Bar | Axis `DepartmentName` · Values `Total Attritions` |
| 📊 Attrition by Age Group | Clustered Column | Axis `Age Group` · Values `Total Attritions` |
| 📈 Attrition Trend | Line Chart (Year > Quarter > Month) | Axis `Year`, `Quarter`, `Month` · Values `Total Attritions` |
| 🍩 Attrition by Gender | Donut (centre: **4,398**) | Legend `Gender` · Values `Total Attritions` |
| 🗺️ Attrition by Location | Map | Location `City` · Size `Total Attritions` |
| 🌳 High-Risk Employee Segment Analysis | Treemap | Group `DepartmentName` · Values `Total Attritions` |
| 🧾 Attrition Details by Department | Table | `Total Attritions`, `Attrition Rate %`, `Avg Exit Tenure (Years)`, `vs PY Attrition Rate %` |

**📉 Attrition by department (top 8)**

| Department | Attritions | Visual |
|---|---|---|
| 🥇 SAP | 575 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🥈 Data Science | 570 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🥉 AI & ML | 563 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 4️⃣ Finance | 556 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 5️⃣ PMO | 552 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 6️⃣ Legal | 540 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 7️⃣ Operations | 534 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 8️⃣ Marketing | 527 | 🟪🟪🟪🟪🟪🟪🟪🟪 |

**📊 Attrition by age group**

| Age Group | Attritions | Share of 8,000 | Visual |
|---|---|---|---|
| 🥇 26–35 | 2,458 | 30.7% | 🟧🟧🟧🟧🟧🟧🟧🟧🟧🟧 |
| 🥈 36–45 | 1,601 | 20.0% | 🟧🟧🟧🟧🟧🟧🟧 |
| 🥉 46–55 | 1,581 | 19.8% | 🟧🟧🟧🟧🟧🟧🟧 |
| 4️⃣ 18–25 | 1,525 | 19.1% | 🟧🟧🟧🟧🟧🟧 |
| 5️⃣ 55+ | 835 | 10.4% | 🟧🟧🟧 |

**🍩 Attrition by gender** — 👩 Female **4,398 (50%)** · 👨 Male **4,398 (50%)**

**🧾 Attrition Details by Department (sample rows)**

| Department | Total Attritions | Attrition Rate % | Avg Exit Tenure |
|---|---|---|---|
| AI & ML | 563 | 16.69% | 3 Years |
| Analytics | 503 | 15.21% | 3 Years |
| Cloud | 517 | 15.56% | 3 Years |
| Consulting | 517 | 15.63% | 3 Years |
| Cyber Security | 513 | 16.00% | 3 Years |
| Data Science | 570 | 16.71% | 3 Years |
| Finance | 556 | 16.76% | 3 Years |
| 🏁 **Total** | **8,000** | **16.00%** | **3 Years** |

> [!NOTE]
> **How to read it:** the trend line sits flat at about **8.00K** for each year from 2022 to 2025, so the yearly view shows overall size rather than month-to-month swings.

> [!TIP]
> ✅ **Reading it:** the **26–35** age group loses the most people, and **Bengaluru** records the highest attrition count (**325**, rate **11.7%**). Average exit tenure is **2.7 years**, down **0.2** from last year.

---

## 💜 Panel 5 — Compensation Analytics

> **Page 3** — Columns, a Bar Chart, a Scatter Chart, a Map, a Donut and a drill-down Matrix.

| Visual | Type | Field Roles |
|---|---|---|
| 📊 Salary Distribution (LPA) | Clustered Column | Axis `Salary Band` · Values `Employees Covered PY` |
| 📉 Average Salary by Department | Clustered Bar | Axis `DepartmentName` · Values `Average Salary` |
| 🪜 Average Salary by Job Level | Clustered Column | Axis `JobLevel` · Values `Avg Salary (₹ LPA)` |
| 🔵 Salary vs Experience | Scatter (colour: performance rating 1–5) | `YearsExperience`, `TotalSalaryLPA`, `PerformanceRating` |
| 🗺️ Salary by Location (LPA) | Map | Location `City` · `Average Salary`, `Employees` |
| 🍩 Salary by Gender | Donut (centre: **11,230**) | Legend `Gender` · Values `Employees Covered PY` |
| 🧮 Compensation Summary | Matrix (Department > Job Level) | `Employees`, `Avg Salary`, `Median`, `Min`, `Highest` |

**📉 Average salary by department**

| Department | Average Salary | Visual |
|---|---|---|
| 🥇 Finance | 33.38 LPA | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🥈 SAP | 33.31 LPA | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🥉 PMO | 33.21 LPA | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 4️⃣ Legal | 33.17 LPA | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 5️⃣ Cyber Security | 33.16 LPA | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 6️⃣ Technology | 33.15 LPA | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |

**🪜 Average salary by job level** — Consultant · Manager · Intern · Partner · Senior Analyst at **27 LPA**; Associate Director · Director · Senior Manager · Senior Consultant · Analyst at **26 LPA**.

**📊 Salary bands in the distribution chart** — 3–6 · 6–9 · 9–12 · 12–15 · 15–20 · 20–30 · 30–40 · 40–50 · 50+ LPA.

**🍩 Salary by gender** — 👩 Female **11,230 (50%)** · 👨 Male **11,230 (50%)**

**🧮 Compensation Summary — AI & ML**

| Row | Avg Salary | Median | Min | Highest |
|---|---|---|---|---|
| **AI & ML** | 26 LPA | 32.87 | 4.55 | 61.7 |
| ↳ Analyst | 25 LPA | 32.13 | 5.90 | 59.14 |
| ↳ Associate Director | 27 LPA | 32.69 | 4.55 | 60.92 |
| 🏁 **Total** | **26 LPA** | **33.01** | **3.78** | **62.74** |

> [!TIP]
> ✅ **Reading it:** pay is very even across departments — the top six sit within **0.23 LPA** of each other (**33.15–33.38 LPA**). The Key Insights note a **13.27%** gender pay gap (Male vs Female) and a **12.50%** rise in average salary.

---

## 🔮 Panel 6 — Performance & Promotion

> **Page 4** — a Column Chart, a Bar Chart, a Donut, a Line Chart, a Map and a drill-down Matrix.

| Visual | Type | Field Roles |
|---|---|---|
| 📊 Performance Rating Distribution | Clustered Column | Axis `PerformanceRating` · Values `Total Employees` |
| 📉 Promotions by Department | Clustered Bar | Axis `DepartmentName` · Values `Dept Promotions` |
| 🍩 Training Status | Donut (centre: **Completed 92.01%**) | Legend `Training Status` · Values `EmployeeID` count |
| 📈 Promotion Trend by Month | Line Chart | Axis `Month` · Values `Promotions` |
| 🗺️ Performers by Location | Map | Location `City` · Size `High Performers` |
| 🧮 Talent Scorecard | Matrix (Department > Team) | `Total Employees`, `Avg Performance Rating`, `Promotions Count`, `Promotion Rate %`, `First Training Status`, `High Performer %`, `High Performers` |

**📉 Promotions by department**

| Department | Promotions | Visual |
|---|---|---|
| 🥇 Technology | 530 | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🥈 Consulting | 420 | 🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🥉 Operations | 310 | 🟪🟪🟪🟪🟪🟪 |
| 4️⃣ Strategy | 205 | 🟪🟪🟪🟪 |
| 5️⃣ Finance | 180 | 🟪🟪🟪 |
| 6️⃣ HR | 150 | 🟪🟪🟪 |
| 7️⃣ Marketing | 120 | 🟪🟪 |

**🍩 Training status** — ✅ Completed **230.01K (92.01%)** · ⏳ Pending **19.99K (7.99%)**

**📈 Promotion trend by month (April → March)**

| Apr | May | Jun | Jul | Aug | Sep | Oct | Nov | Dec | Jan | Feb | Mar |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 82 | 95 | 113 | 126 | 138 | 146 | 158 | 184 | 🔥 **192** | 168 | 152 | 146 |

**🧮 Talent Scorecard (sample departments)**

| Department | Employees | Avg Rating | Promotions | Promotion Rate % | High Performers |
|---|---|---|---|---|---|
| AI & ML | 3,374 | 3.57 | 905 | 26.82% | 1,823 |
| Analytics | 3,306 | 3.58 | 898 | 27.16% | 1,748 |
| Cloud | 3,323 | 3.59 | 914 | 27.51% | 1,812 |
| Consulting | 3,307 | 3.57 | 858 | 25.94% | 1,847 |
| Cyber Security | 3,206 | 3.58 | 864 | 26.95% | 1,789 |
| Data Science | 3,411 | 3.59 | 913 | 26.77% | 1,836 |
| 🏁 **Total** | **50,000** | **3.58** | **13,407** | **26.81%** | **27,223** |

> [!TIP]
> ✅ **Reading it:** promotions climb from **82 in April** to a peak of **192 in December**, then ease back to 146 in March. **Bengaluru** has the most high performers (**688**, **32.1%**), and training completion is **92.0%**.

---

## 🟦 Panel 7 — Executive Summary

> **Page 5** — a Funnel, a Treemap, a Scatter Chart, a Map and a Health Scorecard.

| Visual | Type | Field Roles |
|---|---|---|
| 🪜 Employee Lifecycle Funnel | Funnel | `Stage` · `Headcount` |
| 🌳 Workforce Cost by Department | Treemap | Group `DepartmentName` · Values `Payroll PY (₹ Cr)` |
| 🎯 Attrition % vs Average Salary | Scatter (reference line at **33.00 LPA**) | `DepartmentName` · X `Average Salary` · Y `Attrition Rate %` |
| 🗺️ Employee Distribution by Location | Map | Location `City` · Size `Total Employees` |
| 🩺 Department Health Scorecard | Table with status icons | `Attritionrate`, `AvgRating`, `AvgSalary`, `HealthScore`, `PromotionRate`, `TrainingComp` |

**🪜 Employee lifecycle funnel**

| Stage | Headcount | Conversion | Visual |
|---|---|---|---|
| 📨 Applicant | 48,560 | 100% | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🗣️ Interviews | 18,740 | 38.59% | 🟪🟪🟪🟪 |
| 💼 Offers | 7,850 | 16.17% | 🟪🟪 |
| ✅ Joined | 6,210 | 12.79% | 🟪 |
| 🤝 Retained | 5,620 | 11.57% | 🟪 |

**🩺 Department Health Scorecard**

| Department | Attrition Rate | Avg Rating | Health Score | Promotion Rate | Training Completion |
|---|---|---|---|---|---|
| 🥇 Strategy | 9.90% | 4.30 | **88** | 9.40% | 94.40 |
| 🥈 Consulting | 10.60% | 4.10 | **81** | 9.30% | 93.20 |
| 🥉 Technology | 12.20% | 4.20 | **79** | 9.00% | 93.10 |
| 4️⃣ Finance | 12.10% | 4.00 | **75** | 8.50% | 92.60 |
| 5️⃣ HR | 8.70% | 4.10 | **72** | 8.10% | 90.20 |
| 6️⃣ Operations | 19.30% | 3.80 | **63** | 7.10% | 90.60 |

> [!TIP]
> ✅ **Reading it:** only **11.57%** of applicants end up retained. **Strategy** has the best health score (**88**), while **Operations** is the weakest (**63**) with the highest attrition at **19.30%**.

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| 📊 **Power BI Desktop** | Report authoring, data modelling and visual design |
| 🧮 **DAX** | Measures for attrition, retention, tenure, payroll, promotion and training |
| 🧱 **Power BI Data Model** | Dimension tables, fact tables and summary tables |
| 🧭 **Drill-down Hierarchies** | Business Unit → Department, Department → Team / Job Level and Year → Quarter → Month |
| 🗺️ **Map Visual** | Employees, attritions, salary and high performers by city |
| 🎨 **Native Visuals** | Card, Column, Bar, Line, Donut, Treemap, Scatter, Funnel, Map, Matrix, Table, Slicer |
| 🖼️ **Custom Design** | Purple theme, icons, navigation buttons and a sidebar watermark |

---

## 🏆 Results & Insights

| Panel | Key Insight |
|---|---|
| 👥 **Workforce Overview** | Headcount grew **11.67%** to **50,000**; the eight departments shown are evenly sized at roughly 3.3K–3.5K each |
| ⚠️ **Attrition & Retention** | Attrition rose to **16.00%** (from 12.00% in the Workforce view); retention is **84.00%**; the **26–35** age group leaves the most |
| 💰 **Compensation** | Average salary **33.06 LPA** (+12.50%), median **33.01 LPA**, payroll **16,530 Cr**; department averages stay within about 0.2 LPA |
| ⭐ **Performance** | Average rating **3.58**, promotion rate **26.81%**, **27,223** high performers, training completion **92.01%** |
| 🚀 **Promotions** | **Technology** leads with **530** promotions, then Consulting (**420**); promotions peak in **December** at **192** |
| 🪜 **Hiring Funnel** | **48,560** applicants → **6,210** joined → **5,620** retained (**11.57%**) |
| 🩺 **Department Health** | **Strategy** scores best (**88**); **Operations** scores lowest (**63**) with **19.30%** attrition |
| 🗺️ **Geography** | **Bengaluru** has the largest employee base (**3,020**) and the most high performers (**688**) |

---

## 💡 Advantages

- ⚡ **Fully Interactive** — every card, chart and table responds to the slicers, with no static exports
- 🧭 **Drill-down Everywhere** — go from Business Unit to Department, Team and Job Level, or from Year to Month
- 🆚 **Year-over-year Context** — most KPIs show the previous year and the % change
- 🧑‍💼 **360° HR View** — workforce, attrition, pay, performance and hiring in one report
- 🪜 **Hiring Funnel Included** — see conversion from applicant to retained employee
- 🩺 **Single Health Score** — compare departments on attrition, rating, salary, promotion and training together
- 🧮 **Centralised Measures** — all DAX lives in one `Measure Table`, easy to maintain
- 🗺️ **Map Views** — see where people, exits, pay and top performers concentrate
- 🎨 **Native Visuals Only** — opens cleanly in any standard Power BI Desktop install
- 🎬 **Presentation Included** — a Google Drive walkthrough explains the project end to end
- 🌱 **Room to Grow** — the model is ready for new pages such as recruitment, diversity or learning

---

## ▶️ How to Open & Use

1. 🎬 **[Watch the project presentation on Google Drive](https://drive.google.com/file/d/19MctFShKcMRnU8JcZxusgGeFE_fkEH_N/view?usp=drive_link)** for a guided tour.
2. 💻 Install **Power BI Desktop** (free, Windows).
3. 📂 Open `Accenture_Dashboard.pbix`. The data is stored inside the file, so the visuals load immediately.
4. 🧭 Use the **sidebar buttons** to switch between the five pages.
5. 🖱️ Pick values in the **slicers** to filter every visual, or click a chart segment to cross-filter the rest of the page.
6. 🔍 Use the **drill arrows** on charts and the **+ / −** icons in the tables to move through the hierarchies.

---

## 🎬 Project Presentation

<div align="center">

<a href="https://drive.google.com/file/d/19MctFShKcMRnU8JcZxusgGeFE_fkEH_N/view?usp=drive_link">
  <img src="assets/video_thumbnail.png" alt="Click to watch the Project Presentation" width="760"/>
</a>

**👆 Click the thumbnail to watch the full project presentation on Google Drive**

[![Watch on Google Drive](https://img.shields.io/badge/Google_Drive-Watch_the_Presentation-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/19MctFShKcMRnU8JcZxusgGeFE_fkEH_N/view?usp=drive_link)

</div>

| 🎞️ Detail | Info |
|---|---|
| ☁️ **Hosted on** | Google Drive |
| 🏢 **Project** | Accenture India HR Dashboard |
| 📄 **Pages covered** | Workforce Overview · Attrition & Retention · Compensation Analytics · Performance & Promotion · Executive Summary |
| 🛠️ **Built with** | Power BI Desktop and DAX |

**What the project covers**

| Step | What you will see |
|:---:|---|
| 👥 **1** | The **Workforce Overview** page — headcount, departments, locations, gender mix and hiring trend |
| ⚠️ **2** | The **Attrition & Retention** page — exits by department, age, gender and location |
| 💰 **3** | The **Compensation Analytics** page — payroll, salary bands, job levels and salary vs experience |
| ⭐ **4** | The **Performance & Promotion** page — ratings, promotions, training and the talent scorecard |
| 🧭 **5** | The **Executive Summary** page — lifecycle funnel, workforce cost and the department health scorecard |
| 🎛️ **6** | **Live filtering** with the slicers — every card and chart updates together |

---

## 🖼️ Dashboard Preview

<div align="center">

### 🟪 Page 1 — Workforce Overview

<img src="Dashboard_Overview/Page 1 - Workforce Overview.png" alt="Accenture India — Workforce Overview Dashboard" width="900"/>

*KPI cards, filters, department and location distribution, workforce composition, hiring trend and the business-unit summary.*

<br/>

### 🟣 Page 2 — Attrition & Retention

<img src="Dashboard_Overview/Page 2 - Attrition & Retention.png" alt="Accenture India — Attrition and Retention Analysis" width="900"/>

*Total attritions, attrition and retention rates, exits by department, age group, gender and location, plus the high-risk segment treemap.*

<br/>

### 💜 Page 3 — Compensation & Salary Analytics

<img src="Dashboard_Overview/Page 3 - Compensation Analytics.png" alt="Accenture India — Compensation and Salary Analytics" width="900"/>

*Payroll and salary KPIs, salary distribution, department and job-level averages, salary vs experience and the compensation summary.*

<br/>

### 🔮 Page 4 — Performance & Promotion

<img src="Dashboard_Overview/Page 4 - Performance & Promotion.png" alt="Accenture India — Performance and Promotion Analytics" width="900"/>

*Rating, promotion, high-performer and training KPIs, with promotions by department, the monthly trend and the talent scorecard.*

<br/>

### 🟦 Page 5 — Executive Summary

<img src="Dashboard_Overview/Page 5 - Executive Summary.png" alt="Accenture India — Executive HR Summary Dashboard" width="900"/>

*Headline KPIs, the employee lifecycle funnel, workforce cost, attrition vs salary and the department health scorecard.*

</div>

---

## 📄 License

```
MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
```

---

## 👩‍💻 Author

<div align="center">

| | |
|---|---|
| 👤 **Name** | _KRINA GHORI_ |
| 📊 **Tool** | Power BI Desktop |
| 📁 **Project** | Accenture India HR Dashboard |
| 💡 **Purpose** | Interactive workforce, attrition, compensation and performance analytics dashboard |

<br/>

Made with 💙 using **Power BI**

![Power BI Love](https://img.shields.io/badge/Made%20with-%F0%9F%92%99%20Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

</div>

---

## 🙏 Acknowledgements

- 📊 **Microsoft Power BI Team** — for the report engine and visualization framework behind this dashboard
- 🏢 **Accenture** — whose branding and HR domain inspired this analytics project
- 📖 **Power BI Documentation** — for reference on DAX, drill-down hierarchies, funnels, scatter charts and native visuals
- 💻 **Open Source Community** — for README badge tools (shields.io) and typing SVG animations
- 🎓 **All learners** — who build dashboards like this to sharpen their BI fundamentals

---

<div align="center">

⭐ **Star this repo if you found it helpful!** ⭐

</div>
