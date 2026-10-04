# 🛠️ Data Analyst Tool Stack

> **The tools, platforms and technologies used across the modern Data Analyst workflow.**
>
> You don't need to master everything here.  
> **Master the core stack first. Add tools when the problem requires them.**

---

## 🧭 The Modern Data Analyst Stack

```text
                         📊 DATA ANALYST
                               │
          ┌────────────────────┼────────────────────┐
          │                    │                    │
          ▼                    ▼                    ▼
     📥 DATA SOURCES       🧹 DATA PREP         🔎 ANALYSIS
          │                    │                    │
          │              Power Query             SQL
          │              OpenRefine              Python
          │              KNIME                   pandas
          │              Alteryx                 R
          │
          ▼
      🗄️ DATABASES
          │
    PostgreSQL / MySQL
    SQLite / DuckDB
          │
          ▼
     ☁️ CLOUD WAREHOUSES
          │
   BigQuery / Snowflake
       / Redshift
          │
          ▼
      📊 BI & VIZ
          │
 Power BI / Tableau
 Looker / Metabase
 Superset
          │
          ▼
      💬 STORYTELLING
          │
   Dashboards / Slides
   Datawrapper / Flourish
          │
          ▼
       🚀 PORTFOLIO
          │
   Git + GitHub + Apps
          │
          ▼
       🎯 DECISIONS
```

---

# ⭐ Core Stack

If you're starting your Data Analyst journey, **start here**:

| Skill | Primary Tool | Why |
|---|---|---|
| 📊 Spreadsheet | Microsoft Excel | Core business analysis |
| 🗄️ SQL | PostgreSQL | SQL practice + real database |
| 📈 BI | Power BI | Dashboarding + DAX |
| 🐍 Python | Python + pandas | Analysis + automation |
| 📓 Notebook | Jupyter | Reproducible analysis |
| 🐙 Version Control | Git + GitHub | Portfolio + versioning |
| 📊 Visualization | Power BI / Tableau | Data storytelling |

> 🎯 **You can become job-ready without learning every tool in this repository.**

---

# 📊 1. Spreadsheets

## Microsoft Excel

**Category:** Spreadsheet  
**Best for:** Everyday analytics, reporting, formulas and dashboards

🌐 https://www.microsoft.com/en-us/microsoft-365/excel

### Learn

- Formulas
- Lookup functions
- Pivot Tables
- Charts
- Data Cleaning
- Power Query
- Power Pivot

---

## Google Sheets

**Category:** Spreadsheet  
**Best for:** Collaboration and lightweight analysis

🌐 https://sheets.google.com/

**Free:** ✅

---

# 🧹 2. Data Preparation

## Power Query ⭐

**Category:** Data Preparation

🌐 https://learn.microsoft.com/en-us/power-query/

Use it for:

- Data cleaning
- Transformations
- Combining files
- Repeatable workflows
- Automating recurring reports

---

## OpenRefine

**Category:** Data Cleaning

🌐 https://openrefine.org/

Useful for:

- Messy categorical data
- Standardisation
- Reconciliation
- Large-scale cleaning

---

## Alteryx

**Category:** Data Preparation

🌐 https://www.alteryx.com/

Visual workflow-based data preparation used in enterprise environments.

---

## KNIME

**Category:** Data Preparation

🌐 https://www.knime.com/

Useful for:

- No-code analytics
- Visual workflows
- Data preparation
- Reproducible pipelines

---

# 🗄️ 3. Databases

## PostgreSQL ⭐

🌐 https://www.postgresql.org/

**Best for:** Serious SQL practice and relational database work.

---

## MySQL

🌐 https://www.mysql.com/

Widely deployed relational database.

---

## SQLite

🌐 https://sqlitebrowser.org/

Great for beginners because it doesn't require a database server.

---

## DuckDB 🔥

🌐 https://duckdb.org/

An analytical database designed for fast local analysis.

Especially useful for:

- CSV
- Parquet
- Large local datasets
- SQL-based analysis

---

# ☁️ 4. Cloud Data Warehouses

Once you're comfortable with SQL and databases, explore cloud warehouses.

### Google BigQuery

🌐 https://cloud.google.com/bigquery

**Best for:** Serverless cloud analytics.

### Snowflake

🌐 https://www.snowflake.com/

**Best for:** Enterprise cloud data warehousing.

### Amazon Redshift

🌐 https://aws.amazon.com/redshift/

**Best for:** AWS-centric organizations.

---

# 🔎 5. SQL Clients

## DBeaver ⭐

🌐 https://dbeaver.io/

Universal database GUI for working with multiple databases.

### DataGrip

🌐 https://www.jetbrains.com/datagrip/

Powerful database IDE with strong SQL tooling and autocomplete.

> 💡 Beginners can start with **DBeaver + PostgreSQL**.

---

# 🐍 6. Python Analytics Stack

## Python

🌐 https://www.python.org/

General-purpose language for:

- Data analysis
- Automation
- APIs
- Data cleaning
- Advanced analytics

---

## pandas ⭐

🌐 https://pandas.pydata.org/

The core Python library for DataFrame-based analysis.

---

## NumPy

🌐 https://numpy.org/

Numerical computing foundation behind much of the Python data ecosystem.

---

## matplotlib

🌐 https://matplotlib.org/

Foundational Python visualization library.

---

## seaborn

🌐 https://seaborn.pydata.org/

Statistical visualization built on matplotlib.

---

## Plotly

🌐 https://plotly.com/python/

Interactive visualizations and dashboards.

---

# 📓 7. Analysis Environments

## Jupyter Notebook / JupyterLab ⭐

🌐 https://jupyter.org/

Use for:

- Exploratory Data Analysis
- Documentation
- Visualization
- Reproducible notebooks

---

## Google Colab

🌐 https://colab.research.google.com/

Cloud-hosted notebooks without requiring a local Python setup.

---

## Anaconda

🌐 https://www.anaconda.com/

Python distribution with many data-analysis packages available.

---

## VS Code

🌐 https://code.visualstudio.com/

A powerful editor for:

- Python
- SQL
- Jupyter
- Git
- Project development

---

# 📊 8. Business Intelligence

## Microsoft Power BI ⭐

🌐 https://powerbi.microsoft.com/

Use for:

- Data modeling
- DAX
- Power Query
- Interactive dashboards
- KPI reporting

### Core Power BI Workflow

```text
Raw Data
   ↓
Power Query
   ↓
Data Model
   ↓
Relationships
   ↓
DAX
   ↓
Visuals
   ↓
Dashboard
```

---

## Tableau

### Tableau Public ⭐

🌐 https://public.tableau.com/

Great for building a **public portfolio**.

### Tableau Desktop

🌐 https://www.tableau.com/products/desktop

Full commercial Tableau environment.

---

## Looker Studio

🌐 https://lookerstudio.google.com/

Free Google dashboarding platform.

---

## Metabase

🌐 https://www.metabase.com/

Open-source self-service analytics.

---

## Apache Superset

🌐 https://superset.apache.org/

Open-source BI and dashboarding platform.

---

# 📊 9. Data Storytelling & Visualization

## Datawrapper

🌐 https://www.datawrapper.de/

Excellent for clean, publication-ready charts.

---

## Flourish

🌐 https://flourish.studio/

Useful for:

- Interactive visualizations
- Animated charts
- Presentations
- Data storytelling

---

## Canva / PowerPoint

🌐 https://www.canva.com/

Use for:

- Executive presentations
- Analytics storytelling
- Slide decks
- Business recommendations

> 📌 A great analysis still needs a clear story.

---

# 🧠 10. Problem Framing & Diagramming

## Miro / Excalidraw

🌐 https://excalidraw.com/

Useful before starting analysis:

```text
Business Problem
       ↓
Stakeholders
       ↓
Questions
       ↓
Metrics
       ↓
Data Needed
       ↓
Analysis
```

---

# 🧱 11. Analytics Engineering

## dbt

🌐 https://www.getdbt.com/

Use dbt for:

- SQL transformations
- Data testing
- Documentation
- Data lineage
- Analytics engineering

### Where dbt fits

```text
Raw Data
    ↓
Warehouse
    ↓
dbt
    ↓
Clean Models
    ↓
BI / Analytics
```

> 🔴 Learn this after becoming comfortable with SQL.

---

# 🐙 12. Git & GitHub

## Git + GitHub ⭐

🌐 https://github.com/

Use for:

- Version control
- Portfolio projects
- Collaboration
- Documentation
- Showing your work to employers

### Minimum Git Skills

```text
git clone
git status
git add
git commit
git push
git pull
branch
merge
```

---

# 📱 13. App & Analysis Sharing

## Streamlit

🌐 https://streamlit.io/

Turn Python analysis into a shareable web application.

```text
Python Analysis
      ↓
Streamlit
      ↓
🌐 Interactive App
```

Excellent for portfolio projects.

---

## Hex / Deepnote

🌐 https://hex.tech/

Collaborative notebook platforms supporting SQL and Python workflows.

---

# 📊 14. R & Statistical Analytics

## R + RStudio

🌐 https://posit.co/download/rstudio-desktop/

Useful for:

- Statistics
- Research
- Academic analysis
- Statistical visualization

---

## ggplot2

🌐 https://ggplot2.tidyverse.org/

Grammar-of-graphics visualization library for R.

> 🟡 Optional for most general Data Analyst roles, but valuable for statistics-heavy or research roles.

---

# 📈 15. Product & Web Analytics

## Google Analytics

🌐 https://analytics.google.com/

Useful for:

- Website analytics
- Marketing analytics
- Product analytics
- User behaviour

---

## Mixpanel / Amplitude

🌐 https://amplitude.com/

Useful for:

- Funnels
- Cohorts
- Retention
- Event-based analytics

---

## PostHog

🌐 https://posthog.com/

Open-source product analytics with features such as session replay.

---

# 🤖 16. AI-Assisted Analytics

## Excel Copilot / ChatGPT

🌐 https://chatgpt.com/

Useful for:

- Formula assistance
- SQL explanations
- Debugging
- Data exploration
- Documentation
- Brainstorming
- Automating repetitive tasks

### ⚠️ AI Rule

```text
AI generates
      ↓
You inspect
      ↓
You test
      ↓
You validate
      ↓
You ship
```

> **Never blindly trust AI-generated SQL, formulas or insights.**

---

# 🗃️ 17. Portfolio Databases

## Neon / Supabase

🌐 https://neon.tech/

Useful for creating a real PostgreSQL database for portfolio projects.

Example:

```text
PostgreSQL Database
        ↓
Python / SQL
        ↓
Analysis
        ↓
Power BI / Streamlit
        ↓
🌐 Public Portfolio
```

---

# 🏆 Tool Selection by Career Stage

## 🟢 Beginner

Start with:

```text
Excel
SQL
PostgreSQL
Power BI
Python
pandas
Jupyter
GitHub
```

---

## 🔵 Job-Ready

Add:

```text
Tableau
Power Query
DAX
DuckDB
Streamlit
Cloud Warehouse
Advanced SQL
```

---

## 🔴 Advanced

Explore:

```text
dbt
BigQuery
Snowflake
Redshift
Apache Superset
Metabase
Product Analytics
R
Advanced DAX
Analytics Engineering
```

---

# 🧩 Tool → Problem Mapping

| Problem | Recommended Tool |
|---|---|
| Spreadsheet analysis | 📊 Excel |
| Collaboration | 📊 Google Sheets |
| Data cleaning | 🧹 Power Query |
| SQL practice | 🗄️ PostgreSQL |
| Local analytical SQL | ⚡ DuckDB |
| Database GUI | 🔎 DBeaver |
| Data analysis | 🐍 Python + pandas |
| Visualization | 📈 Power BI |
| Public dashboard | 📊 Tableau Public |
| Google ecosystem reporting | 📊 Looker Studio |
| Open-source BI | 🟢 Metabase / Superset |
| Notebook analysis | 📓 Jupyter |
| Interactive Python app | 🚀 Streamlit |
| Statistical analysis | 📈 R |
| SQL transformation | 🧱 dbt |
| Version control | 🐙 Git + GitHub |
| Cloud warehouse | ☁️ BigQuery / Snowflake |
| Product analytics | 📱 Amplitude / PostHog |
| Portfolio database | 🗃️ Neon / Supabase |
| AI assistance | 🤖 ChatGPT / Copilot |

---

# 🎯 The 80/20 Data Analyst Stack

You **do not need 40 tools** to get hired.

Focus on these first:

```text
       📊 Excel
          +
       🗄️ SQL
          +
      📈 Power BI
          +
       🐍 Python
          +
       🐼 pandas
          +
       🐙 GitHub
          +
      💬 Communication
          │
          ▼
     🎯 JOB READY
```

---

# 🚫 Avoid Tool Collecting

A common beginner mistake:

```text
Excel
SQL
Power BI
Tableau
Python
R
Looker
Metabase
Superset
Snowflake
BigQuery
dbt
Airflow
...
```

Knowing the names of 30 tools doesn't make you a Data Analyst.

Instead:

```text
MASTER
   ↓
Excel
   ↓
SQL
   ↓
One BI Tool
   ↓
Python
   ↓
Business Analysis
   ↓
Projects
```

Then expand based on the job or project.

---

# 🏆 Portfolio Stack

A powerful low-cost portfolio can be built with:

```text
📊 Excel
   ↓
🗄️ PostgreSQL
   ↓
🐍 Python + pandas
   ↓
📈 Power BI / Tableau Public
   ↓
🐙 GitHub
   ↓
🚀 Streamlit
   ↓
🗃️ Neon / Supabase
```

This gives you experience across the complete analytics workflow.

---

# 🧠 The Modern Analyst Workflow

```text
              BUSINESS QUESTION
                     │
                     ▼
                DATA SOURCE
                     │
                     ▼
              🗄️ DATABASE / FILE
                     │
                     ▼
                🧹 CLEANING
                     │
          ┌──────────┴──────────┐
          ▼                     ▼
        🗄️ SQL              🐍 Python
          │                     │
          └──────────┬──────────┘
                     ▼
                  ANALYSIS
                     │
                     ▼
             📊 BI / VISUALIZATION
                     │
                     ▼
               💡 INSIGHTS
                     │
                     ▼
             🗣️ STORYTELLING
                     │
                     ▼
              🎯 RECOMMENDATION
                     │
                     ▼
                💼 DECISION
```

---

# ⭐ Final Rule

> **Tools are not the goal. Better decisions are the goal.**

Learn a tool when it helps you:

**Clean → Query → Analyze → Visualize → Explain → Decide**

### 🚀 Learn fewer tools. Master them deeply. Build real projects.
