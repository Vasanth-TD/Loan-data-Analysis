# 💰 Loan Default Data Analysis

[![Power BI](https://img.shields.io/badge/Power%20BI-yellow)]()

[![SQL Server](https://img.shields.io/badge/SQL%20Server-blue)]()

[![Dataflows](https://img.shields.io/badge/-Dataflows-orange)]()

[![DAX](https://img.shields.io/badge/-DAX-green)]()

## 📊 Dashboard Link  
👉 https://app.powerbi.com/Redirect?action=OpenApp&appId=52e5ef64-afc3-4065-8b92-28b066dcb9e3&ctid=5e81dc77-db51-4a31-8660-6858117beb25&experience=power-bi

---

## 🧩 Problem Statement

The goal of this project is to identify factors influencing **loan defaults** by analyzing borrower demographics, loan purpose, credit scores, and income levels.  
The dashboard empowers financial institutions to enhance **credit risk assessment**, **minimize defaults**, and **improve lending efficiency** through real-time insights.

---

## ⚙️ Steps Followed

1. Installed & configured **Microsoft SQL Server** and **On-Premises Gateway**  
2. Loaded raw dataset into SQL Server  
3. Created **Power BI Dataflow** for centralized cloud ETL  
4. Connected Dataflow to Power BI Desktop  
5. Performed **Data Profiling & Validation** in Power Query  
6. Created **Key DAX Measures** for insights like default rate, YOY loan change, median loan, etc.  
7. Designed three interactive report pages:
   - **Overview**
   - **Financial Risk Metrics**
   - **Applicant Demographics & Profile**
8. Set up **Scheduled & Incremental Refresh** in Power BI Service  
9. Published report and shared it securely with end users  

---

## 🧮 Key DAX Measures

| Metric | DAX Functions Used |
|--------|--------------------|
| Loan Amount by Purpose | `SUMX`, `FILTER`, `ISBLANK` |
| Average Income by Employment Type | `CALCULATE`, `AVERAGE`, `ALLEXCEPT` |
| Default Rate | `COUNTROWS`, `DIVIDE`, `FILTER` |
| Median Loan by Credit Score Category | `MEDIANX`, `VALUES` |
| YOY Loan & Default Change | `CALCULATE`, `DATEADD` |
| YTD Loan Amount | `TOTALYTD`, `CALCULATE` |

---

## 🖼️ Dashboard Snapshots

### 🔹 Overview Page
![Loan Overview Dashboard](Loan%201.png)

### 🔹 Financial Risk Metrics Page
![Financial Risk Metrics Dashboard](Loan%202.png)

### 🔹 Applicant Demographics & Profile Page
![Applicant Demographics Dashboard](Loan%203.png)

---

## 📈 Insights

### 🔸 Loan Overview
- **Total Loans:** 255K | **Total Loan Amount:** 4bn  
- **Average Loan Amount:** 127.58K | **Average Interest Rate:** 13.49%  
- **Home & Business loans** dominate the lending portfolio.  
- **Full-time employees** show higher income and lowest default rate.

### 🔸 Financial Risk Metrics
- **YOY Loan Amount Growth** peaked in 2018.  
- **YOY Default Change** highest in 2015, followed by recovery trend.  
- **Married borrowers with high credit scores** hold majority of total loan volume.

### 🔸 Demographics
- **Median Loan** decreases with declining **credit score**.  
- **Adults & Middle-aged groups** account for highest loan amounts.  
- Borrowers with **dependents and mortgages** exhibit similar loan behavior.  

---

## 🚀 Final Outcome

✅ Created an **end-to-end automated data pipeline** using SQL Server → Dataflows → Power BI  
✅ Designed a **visually interactive dashboard** to monitor defaults & trends  
✅ Enhanced **data-driven decision making** for credit policy & risk management  

---


