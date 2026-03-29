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

### 🔹 Stage 1 Data Envelopment Analysis (DEA) 
We use the following operational variables to calculate efficiency scores:
**Inputs:**
- Total Operating Expenses: Costs of insurance operations (Billion VND).
- Total Debt: Total liabilities (Billion VND).
- Total Equity: Owners' equity (Billion VND).

**Outputs:**
- Financial Investment Income: Revenue from investments (Billion VND).
- Benefits/Losses Incurred: Claims and insurance benefits paid (Billion VND).


### 🔹 Stage 2 (Truncated Regression)
We investigate the determinants of Overall Technical Efficiency (OTE) using these variables:

**Dependent Variable:**
Efficiency score (Range: 0 to 1).

**Independent Variables:**
- Size_log: Log of firm size (total assets)
- Leverage: Debt-to-Equity ratio (%).
- Growth: Annual Net Premium growth rate (%).
- Interest Rate: Market interest rate
- Inflation Rate: Inflation level
- Age: Firm age ( Number of years since establishment). 

**Macroeconomic Independent Variables (Macro):**
- Interest Rate: Annual market interest rate (%).
- Inflation Rate: Annual Consumer Price Index change (%).


##  Data Availability
Due to confidentiality and data source restrictions, the full dataset is not publicly available.

##  Tools
- Data processing: Excel
- Analysis: R

