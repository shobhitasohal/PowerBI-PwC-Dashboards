# 📊 Power BI Dashboards | PwC Power BI Internship Program

Three interactive Power BI dashboards developed as part of the **PwC Power BI Internship Program**, translating complex business data into executive-ready insights across customer service operations, customer retention, and workforce diversity.

---

## 📋 Project Summary

| Dashboard | Business Problem | Solution | Business Outcome |
|---|---|---|---|
| 📞 Call Center Performance | No visibility into agent performance or service bottlenecks | Interactive KPI dashboard tracking 5,000 calls across agents, topics, and time periods | Identified peak demand (12PM–5PM), 19% abandoned call rate, and satisfaction gap of 25% below target |
| 🔄 Customer Churn Analysis | $1.7M annual revenue lost to churn with no understanding of who was leaving or why | Churn segmentation dashboard analyzing demographics, contract type, services, and payment behaviour | Pinpointed month-to-month contracts (88.6% of churn) and senior citizens (41.7% churn rate) as highest-risk segments |
| 🌍 Diversity & Inclusion | Gender imbalance at executive level with no data to explain why progress was stalling | Workforce analytics dashboard tracking hiring, promotions, turnover, and performance by gender and job level | Revealed men secured 64.7% of promotions in FY21 and 100% female turnover in executive part-time roles |

---

## 📞 Dashboard 1 — Call Center Performance

### 🔍 Business Problem
A telecom call centre managing 5,000 monthly customer interactions had no centralized view of agent performance, call resolution rates, or demand patterns — making it impossible to optimize staffing, identify service gaps, or improve customer satisfaction, which was tracking 25% below the target of 4.50.

### 💡 Solution
Designed and developed an interactive Power BI dashboard with dynamic Topic, Quarter, and Month slicers, tracking KPIs across call volume, response speed, resolution rates, agent performance, and satisfaction scores. Built a Top Agent Performance Quadrant ranking the top 5 agents across calls answered, resolved calls, average speed to answer, and satisfaction ratings.

**Key DAX Measures:** Average Answering Speed, Calls Answered Rate, Resolution Rate, Overall Satisfaction Rate, Calls Abandoned Rate

### 📊 Business Outcome
- 📉 Overall satisfaction rate of **3.37 vs. target of 4.50** — a 25.05% gap — flagged for immediate management attention
- ⏰ **Call volumes peak between 12PM–5PM** (2,700 calls) — enabling targeted staffing interventions during critical hours
- 🚨 **19% abandoned call rate** highest in February, directly impacting overall answering rate — recommended additional agents during peak periods
- 🎯 **Streaming services and payment-related inquiries** recorded the highest volume of unresolved calls — identified for targeted agent coaching
- 📅 Weekends busier for payment and contract calls; streaming inquiries spike on Thursdays — enabling smarter scheduling

---

## 🔄 Dashboard 2 — Customer Churn Analysis

### 🔍 Business Problem
A telecom company was losing **1,869 customers** (26.5% churn rate), resulting in **$1.7M in annual revenue loss**, with no structured analysis of who was churning, why they were leaving, or which segments were most at risk — making proactive retention impossible.

### 💡 Solution
Built a comprehensive churn analysis dashboard segmenting 7,000+ customers across demographics, contract types, internet services, payment methods, and tenure. Developed multi-dimensional DAX measures to calculate churn rates by segment and identify the strongest predictors of attrition.

**Key DAX Measures:** Total Churn, Churn %, Customer Lifetime Value, Annual Revenue Lost, Churn by Contract Type, Churn by Service Usage

### 📊 Business Outcome
- 💸 **$1.7M in annual revenue lost** quantified and attributed to specific customer segments for targeted retention action
- 📋 **Month-to-month contract holders account for 88.6% of all churn** — recommended proactive outreach at the 3-month and 24-month contract milestones with exclusive retention offers
- 👴 **Senior citizens churn at 41.7%** — significantly above the 26.5% average — flagged as highest-risk segment, especially those without dependents
- 📡 **Fiber optic internet customers represent 69.4% of churn** — identified for service quality and pricing review
- 🔧 **83.4% of churning customers never used technical support** — recommended proactive support outreach and self-help resources to improve engagement and reduce attrition
- ⏳ **39.8% of customers churn within the first 6 months** — early engagement and onboarding improvement identified as highest-impact retention lever

---

## 🌍 Dashboard 3 — Diversity & Inclusion

### 🔍 Business Problem
An organization struggling with gender imbalance at the executive level had no data infrastructure to understand where diversity gaps were occurring across hiring, promotions, and turnover — or why progress toward gender balance targets was stalling despite stated organizational commitments.

### 💡 Solution
Developed a workforce analytics dashboard analyzing gender-related KPIs across hiring (FY20), promotions (FY21), turnover (FY20), and performance ratings — segmented by job level, department, age group, contract type, and tenure. Identified root causes of gender imbalance at the executive pipeline level.

**Key DAX Measures:** % Male/Female, % Employees Promoted, % Turnover by Gender, Average Performance Rating by Gender, Promotion Rate by Job Level

### 📊 Business Outcome
- 👔 **Men represent 59% of the workforce** with the gap most pronounced in the 30–39 age bracket where men hold a 73% majority
- 📈 **Men secured 64.7% of promotions in FY21** — promotion gap at Director level and above identified for immediate process review and bias audit
- ⚠️ **100% female turnover in executive-level part-time positions** (Job Levels 4, 5, and 6) — a critical retention risk escalated to leadership
- 🏢 **Finance department holds the highest overall turnover rate (11%)** closely followed by Operations and Internal Services at 10%
- 📉 **Job Level 2 (Director) has the highest female turnover rate (50%)** within Operations — targeted retention strategies recommended
- 🎯 Recommended unconscious bias training, structured career development programs, inclusive hiring targets, and exit interviews to address female leadership attrition

---

## 🛠️ Tools & Technical Skills

**Power BI:** Data Modelling · DAX Measures · KPI Cards · Donut & Bar Charts · Performance Quadrants · Dynamic Slicers · Drill-through Pages · Interactive Filtering

**Analytical Skills:** Customer Segmentation · Churn Analysis · Workforce Analytics · KPI Development · Trend Analysis · Data Storytelling · Executive Reporting

---

## 📁 Repository Contents

| File | Description |
|---|---|
| `Call Center Dashboard Project.pbix` | Call centre performance Power BI dashboard |
| `Customer Churn Analysis.pbix` | Customer churn analysis Power BI dashboard |
| `Diversity Inclusion Dashboard.pbix` | DEI workforce analytics Power BI dashboard |
