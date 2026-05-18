# Nigeria 2026 Federal Budget Analysis

## 🧾 Project Overview

This project is a collaborative Power BI analysis of Nigeria’s proposed ₦51.6 trillion 2026 Federal Budget. The analysis transforms complex federal budget data into interactive visual insights focused on:

* budget allocation structure,
* debt servicing pressure,
* ministry spending priorities, and
* capital project execution across sectors.

The project combines **data cleaning**, **modeling**, **DAX calculations**, and **visual storytelling** to provide a clearer understanding of how public funds are distributed across Nigeria’s federal institutions and development priorities.

---

## 🎯 Objectives

This analysis aims to answer key questions such as:

* How is Nigeria’s ₦51.6T budget distributed?
* Which ministries receive the highest allocations?
* How much of the budget goes to debt servicing?
* What is the balance between recurrent and capital expenditure?
* Which sectors dominate federal projects?
* Are projects mostly ongoing or newly initiated?

---

## 📁 Dataset Overview

The project uses cleaned federal budget datasets containing ministry allocations, expenditure categories, and capital project records.

## 1. Budget Summary Table

| Column | Description |
|--------|-------------|
| fund | Spending category (e.g. Debt Service, Capital, Recurrent, Overhead, etc.) |
| total_billion | Total allocation value in billions |
| total_naira | Total budget amount in naira |
| pct_of_total | Percentage share of total budget |

---

## 2. MDA Budget Table

| Column | Description |
|--------|-------------|
| mda | Ministry or agency name |
| capital_ratio | Ratio of capital spending to total allocation |
| total_billion | Total allocation per ministry |
| personnel_naira | Personnel expenditure |
| overhead_naira | Overhead expenditure |
| capital_naira | Capital expenditure |

---

## 3. Capital Projects Table

| Column | Description |
|--------|-------------|
| mda | Responsible ministry/agency |
| project_type | Ongoing or New project |
| total_project_allocation | Budget allocated to project |
| sector | Sector/category of the project |

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- DAX
- Power Query
- Microsoft Excel

---

## ⚙️ Methodology

### Data Preparation
- Cleaned inconsistent ministry names  
- Standardized project categories  
- Converted financial fields into numeric formats  
- Created readable ministry labels  

### Data Modeling
- Built relationships across multiple budget tables  
- Developed reusable DAX measures  
- Designed ministry and project-level analysis structures  

### Visualization Design
- Applied executive dashboard layouts  
- Used storytelling-focused visuals  
- Prioritized readability and insight clarity

---

## 📈 Key KPIs

The dashboard includes:

- Total Budget Allocation  
- Total Capital Allocation  
- Total Number of Projects  
- Average Project Value  
- Share of Ongoing Projects  
- Debt Service Allocation  

---

## 📊 Dashboard Structure

### 🔹 Page 1 — Budget Allocation Overview

#### Focus
Explores how Nigeria’s ₦51.6T budget is distributed across major spending areas.

#### Key Visuals
- Executive KPIs
- Budget breakdown (allocation composition)
- Top ministries by allocation

#### Core Story
Shows how spending is concentrated and how debt obligations shape budget structure before service delivery begins.

---

### 🔹 Page 2 — Debt & Social Spending Analysis

#### Focus
Compares debt servicing against developmental and social investment priorities.

#### Key Visuals
- Debt vs social spending comparison  
- Ministry spending composition
- Social sector KPIs (Education, Health, Agriculture) 

#### Core Story
Highlights the tension between debt obligations and developmental investment priorities.

---

### 🔹 Page 3 — Capital Allocation & Project Delivery

#### Focus
Explores federal project distribution and implementation patterns.

#### Key Visuals
- Capital project KPIs
- Top ministries by project allocation  
- Ongoing vs new project distribution  
- Top MDAs with the most projects  

#### Core Story
Shows where federal projects are concentrated and which ministries dominate project execution.

---

## 🔍 Key Insights

- Debt servicing consumes a significant share of federal expenditure.
- Recurrent expenditure outweighs capital investment.
- Budget allocation is concentrated among a few major MDAs.
- Infrastructure-related ministries dominate project spending.
- Ongoing projects exceed newly initiated projects, suggesting continuation of existing commitments.

---

## 💡 Recommendations

- Increase capital investment in productive sectors.
- Improve the balance between recurrent and developmental spending.
- Strengthen project monitoring and execution mechanisms.
- Enhance transparency around debt servicing and project delivery.
- Improve allocation efficiency across MDAs.

---

## 🚀 Deliverables

- Cleaned datasets
- Published report link
- Project documentation
- Analytical reports

---

```bash
Nigeria-2026-Budget-Analysis/
│
├── cleaned_datasets/
│   ├── budget_summary.csv
│   ├── mda_budget.csv
│   └── capital_projects.csv
│
├── dashboard/
│   └── dashboard_preview.png
│
├── reports/
│   └── nigeria_2026_budget_analysis.pdf
│
└── README.md
```
---

## 👥 Team Collaboration

This project was developed collaboratively as part of a group data analytics internship.

Contributions included:

- Data cleaning  
- Data modeling  
- DAX development  
- Dashboard design  
- Insight generation  

---

## 📚 Dataset Reference

Budget Office of the Federation. (2025). *2026 Federal Government of Nigeria Budget Proposal and Capital Project Allocations*. Federal Government of Nigeria.

Federal Government of Nigeria. (2025). *2026 Appropriation Bill and Budget Allocation Reports*. Abuja, Nigeria.

---

## 🔗 Acknowledgment

Completed as part of the HNG Data Analytics Internship Program.

---

## 👤 Author  
Emmanuel Achugo  
Data Analyst  
SQL • Python • Data Visualization • Machine Learning
