# RegretIQ — Purchase Regret & Return Behavior Intelligence

> **Simulated Startup Project | RetailPulse Analytics**
> Built by: Chinu (BI Analyst) | Environment: Startup Team Simulation

---

## Project Overview

RegretIQ is a business intelligence project that analyzes **why customers return products** in an e-commerce environment — and surfaces actionable insights to reduce return rates, improve customer experience, and protect revenue.

This project is built in a simulated startup environment (RetailPulse Analytics), structured around real-world workflows including sprint planning, daily standups, stakeholder reviews, and documented meeting notes.

---

## Simulated Company

**Company:** RetailPulse Analytics
**Type:** Early-stage D2C analytics startup
**Mission:** Help e-commerce brands understand and reduce purchase regret

---

## Dataset

**Source:** E-Commerce Order & Supply Chain Dataset (Kaggle)
**Period:** September 2016 – September 2018
**Train set:** 89,316 rows across 5 tables
**Test set:** 38,279 rows across 5 tables (used for ML in Sprint 5+)

### Tables
| Table | Key Columns |
|---|---|
| Orders | order_id, customer_id, order_status, timestamps |
| OrderItems | order_id, product_id, seller_id, price, shipping_charges |
| Customers | customer_id, city, state |
| Payments | order_id, payment_type, installments, value |
| Products | product_id, category, weight, dimensions |

---

## 🗺️ Project Sprint Plan

| Sprint | Focus | Tools |
|---|---|---|
| Sprint 1 | Environment Setup + Data Ingestion + Data Quality Audit | PostgreSQL, Python, Excel |
| Sprint 2 | Exploratory Data Analysis (EDA) | Python (Pandas, Seaborn, Plotly) |
| Sprint 3 | SQL Deep-Dive — Return Behavior Analysis | SQL (Advanced) |
| Sprint 4 | dbt — Data Modeling & Transformation | dbt |
| Sprint 5 | RFM Segmentation + Cohort Analysis | Python + SQL |
| Sprint 6 | Dashboard 1 — Operations View | Power BI |
| Sprint 7 | Dashboard 2 — Executive View | Tableau |
| Sprint 8 | Final Storytelling, GitHub Polish & Presentation | All tools |

---

## Folder Structure


regretiq/
│
├── README.md
├── data/
│   ├── raw/
│   │   ├── train/          # Primary working dataset
│   │   └── test/           # Used for ML in Sprint 5+
│   └── processed/          # Cleaned & transformed outputs
├── sql/
│   ├── ingestion/          # Table creation & data loading scripts
│   ├── analysis/           # Sprint 3 analytical queries
│   └── views/              # Reusable SQL views
├── python/
│   ├── notebooks/          # Jupyter notebooks per sprint
│   └── scripts/            # Reusable Python scripts
├── dbt/
│   ├── models/             # dbt transformation models
│   └── tests/              # dbt data tests
├── dashboards/
│   ├── powerbi/            # .pbix files
│   └── tableau/            # .twbx files
├── excel/                  # Risk scoring & ad-hoc analysis
├── docs/
│   ├── meeting_notes/      # Sprint kickoffs, standups, reviews
│   └── sprint_reviews/     # End-of-sprint findings & sign-offs
└── presentations/          # Stakeholder decks



##  Tools & Stack

- **SQL:** PostgreSQL (pgAdmin)
- **Python:** Pandas, Seaborn, Plotly, Scikit-learn
- **Transformation:** dbt
- **Dashboards:** Power BI, Tableau
- **Ad-hoc Analysis:** Excel
- **Version Control:** GitHub

---


