# Data Quality Governance & Health Monitoring Report
**Live Dashboard → [View Here](https://saivarnika-ba.github.io/data-quality-audit)**

> Built with Power BI · SQL · Data Governance · ETL Validation · Excel

---

## Business Problem
Downstream Power BI reports were silently consuming dirty data — missing values, duplicates, and inconsistencies across 6,000+ records were only discovered after they had already distorted business decisions. There was no proactive monitoring layer between the data source and the reports.

## What I Built
A **real-time data health monitoring dashboard** that acts as a quality gate before data reaches production reporting:

- **4 DQ dimensions tracked** — Completeness, Accuracy, Consistency, Uniqueness — each with its own KPI and threshold
- **SQL-based ETL validation scripts** — profiling queries that flag anomalies at source before load
- **RAG status conditional formatting** — Red / Amber / Green indicators make quality signals instantly readable for non-technical stakeholders (no data literacy required)
- **Smart alerting visuals** — colour-coded tiles that change state automatically when a dimension breaches threshold
- **Data governance documentation** — validation rules and recommended controls written up as a governance spec

## Key Findings
| Finding | Detail |
|---|---|
| 12% missing or duplicate records detected | Identified before reaching downstream reports |
| 4 DQ dimensions monitored in real time | Completeness · Accuracy · Consistency · Uniqueness |
| Estimated error reduction | ~20% reduction in reporting errors if controls implemented |

## Why This Project Matters
Most junior analysts build dashboards *on top of* data. This project sits *underneath* — it's the layer that decides whether data is trustworthy enough to report on. That's a data engineering and governance mindset, not just a visualisation skill.

## Technical Stack
| Layer | Tool |
|---|---|
| Validation | SQL — profiling queries, NULL checks, duplicate detection, referential integrity |
| ETL | Python (Pandas) — data cleaning pipeline before load |
| Monitoring Dashboard | Power BI — RAG conditional formatting, smart alerting tiles |
| Governance Docs | Excel — validation rules, threshold definitions, remediation log |

## Files in This Repo
```
index.html          → Live interactive dashboard (open in browser)
README.md           → This file
```

## Skills Demonstrated
`Data Governance` `Data Quality` `ETL Validation` `SQL` `Power BI` `Conditional Formatting` `RAG Status` `Master Data Management` `Completeness` `Accuracy` `Consistency` `Uniqueness`

---
*Part of my analytics portfolio → [saivarnika-portfolio.netlify.app](https://saivarnika-portfolio.netlify.app)*# dashboard-monitoring
