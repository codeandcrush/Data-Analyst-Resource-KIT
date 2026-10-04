# 🎤 Data Analyst Interview Preparation

> **Interviews don't test whether you watched a course. They test whether you can think, solve, explain and make decisions with data.**

Use this section after completing the roadmap, projects and practice labs.

---

# 🧭 Interview Preparation Framework

```text
FOUNDATION
   ↓
SQL + Excel + Statistics
   ↓
CORE
   ↓
Python + Visualization + Business
   ↓
ADVANCED
   ↓
Performance + Experimentation + Forecasting
   ↓
COMMUNICATION
   ↓
Project Deep-Dive + Stakeholder Questions
   ↓
🎯 INTERVIEW READY
```

---

# 🗄️ SQL Interview Questions

| Level | Question | What It Tests |
|---|---|---|
| 🟢 Foundation | Get the most recent order per customer. | Window functions |
| 🟢 Foundation | Find customers who have never placed an order. | LEFT JOIN / NOT EXISTS |
| 🟡 Core | Calculate month-over-month revenue growth. | LAG + date grouping |
| 🟡 Core | Find the top 3 products by revenue in each category. | ROW_NUMBER / RANK |
| 🟢 Foundation | Difference between INNER JOIN and LEFT JOIN? | Join fundamentals |
| 🟢 Foundation | Why does `COUNT(*)` differ from `COUNT(column)`? | NULL semantics |
| 🟢 Foundation | Difference between WHERE and HAVING? | Filtering vs aggregation |
| 🟡 Core | Calculate a running total of daily revenue. | Window frames |
| 🟡 Core | Deduplicate a table while keeping the latest row per key. | Real-world data cleaning |
| 🟡 Core | Write a 7-day rolling average. | Window functions + dates |
| 🔴 Advanced | A query is slow on 50M rows. What do you check? | Performance thinking |
| 🟡 Core | Explain a CTE and when you'd use it over a subquery. | Readability + reuse |

These questions deliberately emphasize practical analyst SQL rather than syntax memorisation. The source includes window functions, NULL behaviour, deduplication, rolling averages and query performance.

### 🎯 SQL Interview Standard

You should be able to solve these **without searching for syntax**:

```text
JOIN
GROUP BY
HAVING
CASE
CTE
Subquery
Date Logic
NULL Handling
Window Functions
LAG / LEAD
ROW_NUMBER / RANK
Running Totals
Rolling Averages
Deduplication
```

---

# 📊 Excel Interview Questions

| Level | Question | What It Tests |
|---|---|---|
| 🟢 Foundation | VLOOKUP vs XLOOKUP? | Modern Excel knowledge |
| 🟢 Foundation | Build a Pivot Table summarising two dimensions. | Live Excel ability |
| 🟡 Core | When would you use INDEX MATCH instead of VLOOKUP? | Flexible lookups |
| 🟡 Core | A weekly report is rebuilt manually. Automate it. | Power Query thinking |
| 🟢 Foundation | How would you find and handle duplicates? | Practical cleaning judgement |

The source focuses on live Excel ability, lookups, Pivot Tables, cleaning and automation rather than memorising functions.

---

# 📈 Statistics Interview Questions

| Level | Question | What It Tests |
|---|---|---|
| 🟢 Foundation | Mean vs median—and when can each mislead? | Distribution thinking |
| 🟢 Foundation | Correlation vs causation: give an example. | Analytical reasoning |
| 🟡 Core | What does a p-value of 0.04 actually mean? | Statistical precision |
| 🔴 Advanced | An A/B test is significant after 2 days. Do we ship? | Experiment judgement |
| 🟡 Core | Average order value rose but revenue fell. Explain. | Mix effects |
| 🟡 Core | A survey has a 4% response rate. What does that mean? | Sampling bias |
| 🟡 Core | How would you detect and handle outliers? | Analytical judgement |
| 🔴 Advanced | How large a sample do you need for this test? | Power analysis |

The questions explicitly test whether candidates understand uncertainty, bias, experiment design and the consequences of analytical decisions.

---

# 🧹 Data Cleaning Questions

| Level | Question | What It Tests |
|---|---|---|
| 🟡 Core | 20% of a column is NULL. What do you do? | Drop vs impute vs flag |
| 🟡 Core | Are these two records the same customer? | Entity resolution |
| 🟢 Foundation | A date column imported as text. Fix it at scale. | Practical cleaning |
| 🟡 Core | How would someone else reproduce this analysis? | Documentation |

> **Important:** Cleaning isn't just pressing a button. Every cleaning decision can change the answer.

The source specifically highlights NULL handling, entity resolution, date parsing and reproducibility as interview-level data-cleaning skills.

---

# 📊 Visualization Interview Questions

| Level | Question | What It Tests |
|---|---|---|
| 🟢 Foundation | Why not use a pie chart here? | Chart-selection judgement |
| 🟡 Core | What's misleading about this chart? | Honest visualization |
| 🟡 Core | A dashboard has 14 charts. Improve it. | Editing + prioritisation |
| 🟡 Core | Design a dashboard for a Sales Director. | Audience thinking |
| 🔴 Advanced | Measure or calculated column in Power BI? | DAX + performance |
| 🟡 Core | How do you make a chart accessible to colour-blind readers? | Accessibility |

The source stresses that good visualization is about **judgement and communication**, not simply knowing how to create charts.

---

# 💼 Business & Case Questions

| Level | Question | What It Tests |
|---|---|---|
| 🟡 Core | Define "active user" for this product. | Metric definition |
| 🟡 Core | Signup conversion fell 8%. Investigate. | Structured diagnosis |
| 🟡 Core | Is retention improving? How would you check? | Cohort thinking |
| 🟡 Core | Which customers should marketing target? | Segmentation |
| 🟡 Core | Is this campaign profitable? What do you need? | Asking for missing data |
| 🟡 Core | Someone asks you to pull sales numbers. What do you ask? | Clarifying the decision |
| 🔴 Advanced | How would you forecast next quarter? | Method + assumptions |
| 🟡 Core | Estimate the number of taxis in this city. | Guesstimation |

A strong analyst doesn't immediately calculate. **First understand the decision.**

---

# 🐍 Python Interview Questions

| Level | Question | What It Tests |
|---|---|---|
| 🟡 Core | Reproduce this SQL query in pandas. | Real pandas fluency |
| 🔴 Advanced | A file is too large for memory. What do you do? | Chunking / tooling |
| 🟡 Core | Difference between merge, join and concat? | Practical pandas knowledge |
| 🔴 Advanced | Make this pandas operation faster. | Vectorisation + dtypes |

The source focuses on practical pandas operations and performance rather than tutorial-style Python questions.

---

# 🗣️ Communication Questions

Technical skill gets you into the interview.

**Communication helps you get hired.**

| Level | Question | What It Tests |
|---|---|---|
| 🟡 Core | Summarise this analysis in five sentences. | Synthesis |
| 🟡 Core | Explain this result to a marketing manager. | Non-technical communication |
| 🟡 Core | The VP says your numbers are wrong. What do you do? | Handling pushback |
| 🔴 Advanced | Your analysis contradicts leadership expectations. Now what? | Integrity + diplomacy |

The source treats communication as a core analytical competency, including handling disagreement without becoming defensive or abandoning the evidence.

---

# 🚀 Project & Behavioral Questions

These are among the highest-signal questions because they reveal whether you actually built your portfolio.

| Level | Question | What It Tests |
|---|---|---|
| 🟡 Core | Walk me through your favourite project end to end. | Project ownership |
| 🟡 Core | What would you do differently if you redid it? | Self-awareness |
| 🟡 Core | How do you prioritise when 3 people need analysis simultaneously? | Stakeholder management |
| 🟡 Core | How do you use AI tools, and where don't you trust them? | Modern analytical judgement |
| 🟢 Foundation | Why data analysis, and why this industry? | Motivation + company research |

The source specifically calls the end-to-end project walkthrough the **highest-signal interview question** and includes AI-tool judgement as an increasingly relevant 2026 topic.

---

# 🏆 How to Prepare Your Favourite Project

You should be able to explain one project without opening your laptop.

Use this structure:

```text
1. Business Problem
        ↓
2. Dataset
        ↓
3. Cleaning
        ↓
4. Methodology
        ↓
5. Key Finding
        ↓
6. Business Impact
        ↓
7. Recommendation
        ↓
8. What I Would Improve
```

### 🎤 5-Minute Project Test

Try explaining your project in **5 minutes**.

If you need 20 minutes to explain it, you probably haven't simplified the story enough.

---

# ⏱️ Interview Practice Mode

### Round 1 — Untimed

Focus on correctness.

### Round 2 — Timed

Solve SQL and business cases under pressure.

### Round 3 — Explain While Solving

Talk through your reasoning.

### Round 4 — Follow-up Questions

Assume the interviewer challenges every assumption.

### Round 5 — Mock Interview

Complete an entire interview without notes.

---

# 🔥 Final Interview Readiness Checklist

Before applying seriously, make sure you can:

- [ ] Solve common SQL joins without hesitation
- [ ] Use window functions comfortably
- [ ] Explain NULL behaviour
- [ ] Build a Pivot Table live
- [ ] Explain XLOOKUP / INDEX-MATCH
- [ ] Explain p-values correctly
- [ ] Discuss correlation vs causation
- [ ] Handle A/B-test questions
- [ ] Explain your data-cleaning decisions
- [ ] Critique a misleading visualization
- [ ] Design a dashboard for a specific audience
- [ ] Define business metrics clearly
- [ ] Diagnose a business KPI drop
- [ ] Solve pandas problems
- [ ] Explain your best project end-to-end
- [ ] Handle stakeholder pushback
- [ ] Explain how you use AI responsibly
- [ ] Answer "Why Data Analytics?"
- [ ] Complete a mock interview

---

# 🎯 The Interview Rule

> **Don't memorise answers. Learn the reasoning behind them.**

A strong candidate doesn't sound like:

> "I know the syntax for this."

They sound like:

> **"Here's how I'd approach the problem, here's what I'd check first, here's the assumption I'm making, and here's how I'd validate the result."**

That's what turns **technical knowledge into analyst judgement**.

---

## 🧠 Final Interview Formula

```text
KNOW THE TOOL
     +
SOLVE THE PROBLEM
     +
EXPLAIN YOUR REASONING
     +
UNDERSTAND THE BUSINESS
     +
DEFEND YOUR DECISION
     =
🎯 HIREABLE DATA ANALYST
```
