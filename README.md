# Kenya-insurance-district-analysis
District-level performance analysis for bank loan insurance portfolios. Tracks total loan amounts (value insured), premiums, claims, and loss ratios through an interactive dashboard.
# 📊 Kenya Insurance District Analysis

## 🧩 Project Overview

This project analyzes district-level agricultural insurance performance across Kenya.  
The goal is to evaluate portfolio risk, profitability, and exposure concentration at the district level. Insights from this analysis help optimize underwriting, pricing strategies, and risk diversification.

---

## 🎯 Objectives

- Measure **Total Value Insured** per district  
- Calculate **Total Premium Collected**  
- Compute **Net Claims Paid**  
- Derive **Loss Ratio** by district  
- Classify districts by **risk level**  
- Identify profitable vs high-risk districts for strategic decision-making

---

## 📁 Dataset Structure

The dataset contains district-level agricultural insurance portfolio data with the following columns:

| Column Name | Description |
|-------------|-------------|
| S/N | Serial number for each insured farmer |
| NAME | Farmer’s full name |
| Farm Location By District | District of the farm |
| CROP PLANTED | Crop insured |
| FARM SIZE (ACRES) | Farm size in acres |
| VALUE TO INSURE | Total monetary value insured for the farm (UGX) |
| PERCENTAGE LOSS | Percentage of yield lost |
| CLAIM PAYABLE (UGX) | Gross claim amount before deductions |
| LESS EXCESS | Deductible/excess applied |
| NET CLAIM PAYABLE (UGX) | Final claim amount paid after deductions |
| Premium Amount | Insurance premium paid by the farmer |
| Season | Agricultural season covered |
| YEAR | Year of coverage |

---

## 📐 Key Metrics & Formulas

- **Total Value Insured** – Amount at risk per district  
- **Total Premium** – Revenue collected from premiums  
- **Net Claims Paid** – Actual claims disbursed after excess/deductible  
- **Loss Ratio** – Measure of claims vs premium

\[
{Loss Ratio} = {Net Claims Paid}}/{{Premium Amount}}
\]

- **Average % Loss** – Yield loss severity across farms in a district

---

## 🛠 Tools & Technology Used

- **Google Sheets** – Data cleaning, aggregation, and calculations  
- **Looker Studio** – Interactive dashboards & visualization  
- **GitHub** – Project version control and portfolio showcase  

---

## 📊 Dashboard Preview

*(Screenshots to be added in the `screenshots/` folder)*

![Overview](screenshots/overview.png)  
![District Metrics](screenshots/district_comparison.png)  
![Loss Ratio Analysis](screenshots/loss_ratio_analysis.png)  
![Premium vs Claims](screenshots/premium_vs_claims.png)

---

## 🌍 Live Interactive Dashboard

[View Dashboard in Looker Studio](https://lookerstudio.google.com/reporting/e64d9fde-04b9-4ecc-80fe-60a15a94b334)

---

## 🔎 Key Insights

- Districts with **high insured value but low loss ratio** are strong underwriting zones  
- Some districts have **high claim volatility**, requiring pricing review or exposure limits  
- Premium concentration highlights **portfolio exposure risk**  
- Crop-specific risk analysis shows which crops drive higher claims  

---

## 📈 Business Value

- Helps insurers **optimize underwriting and pricing strategies**  
- Reduces **portfolio volatility** by identifying high-risk zones  
- Guides **strategic expansion and risk diversification**  
- Provides actionable insights for **district-level decision making**

---

## 👤 Author

**[IRINATWE JOHN]** – Actuarial Science | Insurance Analytics | Climate Risk Modeling  

---

## 📂 Folder Structure
