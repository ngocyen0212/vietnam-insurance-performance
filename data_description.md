# 📊 Data Description

## 📌 Overview
This project uses panel data of 30 insurance companies in Vietnam from 2016 to 2022, including both life (14 firms) and non-life insurers (16 firms).

## 🏢 Data Sources
- Firm-level data: Audited financial statements and reports from the Insurance Supervisory Authority (Ministry of Finance)
- Macroeconomic data: General Statistics Office of Vietnam and State Bank of Vietnam
- Additional financial data from public financial databases

## 📈 Dataset Structure
- Panel data: firm-year observations
- Each observation includes:
  - Company name
  - Year
  - Business type (life / non-life)

##  Variables

### 🔹 Stage 1 (DEA)
**Inputs:**
- Total Operating Expenses
- Total Debt
- Total Equity

**Outputs:**
- Financial Investment Income
- Benefits/Losses Incurred

### 🔹 Stage 2 (Truncated Regression)

**Dependent Variable:**
- OTE (Overall Technical Efficiency, range [0,1])

**Independent Variables:**
- Size_log: Log of firm size (total assets)
- Leverage: Debt ratio
- Growth: Premium growth rate
- Interest Rate: Market interest rate
- Inflation Rate: Inflation level
- Age: Firm age

##  Data Availability
Due to confidentiality and data source restrictions, the full dataset is not publicly available.

##  Tools
- Data processing: Excel
- Analysis: R
