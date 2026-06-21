## 📌 Project Overview

The **Hospital Operations & Patient Risk Intelligence Dashboard** is an end-to-end healthcare analytics project designed to help hospital leadership monitor operational performance, patient risk factors, financial outcomes, and resource utilization.

The project simulates a real-world healthcare environment where data is collected from multiple systems including admissions, billing, pharmacy, laboratory, follow-up, and patient management systems. The objective is to identify key drivers of readmissions, treatment costs, claim rejections, and operational inefficiencies while enabling data-driven decision making.

This project demonstrates skills in:

* SQL Data Analysis
* Python Data Cleaning & Feature Engineering
* Data Quality Auditing
* Exploratory Data Analysis (EDA)
* Business Intelligence & Dashboarding
* Healthcare Analytics
* KPI Development
* Stakeholder Reporting

---

# 🎯 Business Problem

A multi-city hospital group is experiencing:

* Rising patient readmission rates
* Increasing treatment costs
* High insurance claim rejections
* Poor follow-up compliance
* Inconsistent data across operational systems

Management wants to understand:

> Which operational, clinical, and financial factors are driving patient readmission risk and increasing healthcare costs?

The goal is to reduce avoidable readmissions, improve patient outcomes, optimize resource allocation, and enhance operational efficiency.

---

# 🗂 Dataset Overview

The project uses a relational healthcare dataset consisting of multiple interconnected tables.

| Table           | Description                                 |
| --------------- | ------------------------------------------- |
| Patients        | Patient demographic and medical information |
| Admissions      | Hospital admission records                  |
| Treatments      | Treatment and procedure details             |
| Billing Claims  | Financial and insurance claims data         |
| Pharmacy Orders | Medication and prescription records         |
| Lab Results     | Laboratory test results                     |
| Follow-Ups      | Post-discharge follow-up records            |
| Doctors         | Doctor information                          |
| Departments     | Hospital department details                 |
| Hospitals       | Hospital branch information                 |

### Dataset Scale

| Table           | Approximate Records |
| --------------- | ------------------- |
| Patients        | 12,090              |
| Admissions      | 30,130              |
| Treatments      | 90,160              |
| Billing Claims  | 30,080              |
| Pharmacy Orders | 70,090              |
| Lab Results     | 60,000              |
| Follow-Ups      | 30,000              |

---

# 🔍 Data Quality Challenges

The dataset intentionally contains real-world data issues:

### Missing Values

* Age
* City
* Chronic Condition
* Diagnosis
* Treatment Cost
* Billing Amount
* Lab Values

### Data Inconsistencies

* Gender values (M, Male, F, Female)
* Claim Status variations
* Readmission status mismatches

### Outliers

* Invalid ages
* Extremely high treatment costs
* Negative costs

### Duplicate Records

* Patient duplicates
* Admission duplicates
* Billing duplicates
* Pharmacy duplicates

### Referential Integrity Issues

* Missing foreign keys
* Orphan patient IDs
* Invalid admission references

---

# 🛠 Tools & Technologies

| Tool       | Purpose                             |
| ---------- | ----------------------------------- |
| SQL        | Data Extraction & Analysis          |
| Python     | Data Cleaning & Feature Engineering |
| Pandas     | Data Processing                     |
| NumPy      | Numerical Operations                |
| Matplotlib | Visualization                       |
| Seaborn    | Exploratory Analysis                |
| Power BI   | Dashboard Development               |
| Excel      | Data Validation                     |

---

# 📊 Key KPIs

### Patient Metrics

* Total Patients
* Readmission Rate
* High-Risk Patients
* Follow-Up Completion Rate

### Operational Metrics

* Total Admissions
* Average Length of Stay
* Department Utilization
* Hospital Load Analysis

### Financial Metrics

* Total Revenue
* Average Gross Bill
* Claim Rejection Rate
* Cost Per Patient

### Clinical Metrics

* Chronic Disease Analysis
* Readmission Trends
* Treatment Cost Analysis
* Risk Score Assessment

---

# ⚙️ Project Workflow

## 1. Data Understanding

* Reviewed healthcare business requirements
* Studied relational schema
* Identified primary and foreign keys

## 2. Data Cleaning

* Removed duplicates
* Handled missing values
* Standardized categorical variables
* Fixed data inconsistencies

## 3. Feature Engineering

Created new analytical features:

* Length of Stay
* Readmission Gap Days
* Total Treatment Cost
* Total Pharmacy Cost
* Follow-Up Status
* Chronic Disease Flag
* High-Cost Patient Flag
* Patient Risk Score

## 4. Exploratory Data Analysis

Performed analysis on:

* Patient demographics
* Admission trends
* Readmission behavior
* Cost drivers
* Department performance
* Hospital performance

## 5. Dashboard Development

Built an interactive Power BI dashboard providing:

* Executive Overview
* Patient Risk Analysis
* Financial Performance Monitoring
* Operational Efficiency Tracking
* Readmission Intelligence

---

# 📈 Dashboard Insights

### Patient Risk Intelligence

* Identified patient groups with highest readmission risk.
* Analyzed chronic disease impact on hospital utilization.

### Cost Optimization

* Highlighted high-cost departments and procedures.
* Identified major contributors to treatment expenses.

### Operational Performance

* Evaluated hospital occupancy and resource utilization.
* Measured average length of stay and admission trends.

### Financial Analytics

* Monitored claim rejection patterns.
* Tracked revenue and billing performance.

---

# 💡 Business Recommendations

### Reduce Readmissions

* Strengthen discharge planning.
* Improve post-discharge monitoring.
* Increase follow-up compliance.

### Improve Operational Efficiency

* Optimize resource allocation.
* Monitor department workloads.
* Reduce avoidable patient stay durations.

### Financial Optimization

* Improve claim documentation quality.
* Reduce claim rejection rates.
* Track high-cost treatment patterns.

---

# 📸 Dashboard Preview

<img width="1327" height="747" alt="image" src="https://github.com/user-attachments/assets/a6963c83-049e-40dc-9c4a-db9561eb326b" />




---

# 🚀 Project Outcome

This project demonstrates practical experience in healthcare analytics, business intelligence, SQL, Python, data cleaning, KPI development, dashboard design, and stakeholder-focused reporting. It showcases the complete data analytics lifecycle from raw data processing to executive-level decision support.
