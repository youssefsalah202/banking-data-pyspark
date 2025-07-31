# 📊 Exploring Banking Data Using PySpark

This project focuses on analyzing a real-world **bank marketing dataset** using **Apache Spark** through **PySpark** in a Jupyter Notebook. The dataset originates from a Portuguese banking institution and contains details about clients contacted during a marketing campaign. The goal is to extract business insights, identify patterns in client behavior, and evaluate campaign performance — all using scalable big data tools.

---

## 📌 Project Goals

- Use **PySpark** for scalable data exploration and preprocessing.
- Perform **Exploratory Data Analysis (EDA)** on demographic and campaign-related features.
- Identify **factors influencing client subscription** to a term deposit.
- Evaluate **campaign performance** across different customer segments.
- Demonstrate practical use of **big data processing techniques** in banking/finance analytics.

---

## 📂 Dataset Overview

The dataset includes the following types of features:
- **Client Information**: age, job, marital status, education, balance
- **Contact Info**: contact type (cellular, telephone), last contact day/month/duration
- **Campaign Info**: number of contacts, outcome of previous campaigns
- **Target Variable**: whether the client subscribed to a term deposit (`yes` / `no`)

---

## 🔧 Tools & Technologies

- **Python 3**
- **Apache Spark (PySpark)**
- **Jupyter Notebook**
- **Spark DataFrames**
- **Matplotlib / Seaborn** (for visualizations)
- **Pandas** (minor use for comparison if needed)

---

## 🔍 Key Analyses & Features

- **Data Loading & Cleaning**:
  - Loaded CSV data using PySpark’s `read.csv` method.
  - Handled missing values and formatted columns.

- **Data Exploration**:
  - Analyzed **customer demographics** (age, job, marital status).
  - Explored **balance distributions** across segments.
  - Investigated **contact methods** and **campaign effectiveness**.

- **Target Variable Analysis**:
  - Compared characteristics of customers who subscribed vs. those who didn’t.
  - Visualized outcomes to find patterns and correlations.

- **Business Insights**:
  - Identified optimal times/months for customer outreach.
  - Recommended more effective contact methods based on outcomes.
  - Suggested targeting strategies based on age, job, and previous interactions.

---

## 📈 Example Insights

- Customers aged **30–40** were more likely to subscribe to term deposits.
- **Cellular contact** outperformed telephone in conversion rates.
- Previous positive contact (`poutcome = success`) highly increased success odds.
- **May and August** were peak months for positive responses.


