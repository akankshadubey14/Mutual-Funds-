# 📊 Mutual Fund Analysis – Top 30 High-Return, Low-Risk Schemes

This project aims to identify the **top 30 mutual fund schemes** offering **maximum returns with minimum risk** by leveraging Python, Excel, and Power BI.

---

## 🛠️ Tools & Technologies

- **Python** (Pandas, Scikit-learn): Data wrangling, analysis, scoring  
- **Excel**: Data formatting, validation  
- **Power BI**: Interactive visualization

📁 **Dataset Size**: 2500+ mutual fund schemes  
✅ **Final Output**: Top 30 best-performing, low-risk mutual funds

---

## 🎯 Project Objective

To help investors make informed decisions by finding mutual funds with:
- Strong long-term returns  
- Low expense ratios  
- Stable performance  
- Moderate risk levels  

All insights are delivered via an **interactive Power BI dashboard**.

---

## 🐍 Python-Based Analysis

### 📂 Dataset:  
[Mutual_Funds.csv](https://github.com/niravtrivedi23/Mutual-Fund-Analysis/blob/main/Mutual_Funds.csv)

### ✅ Key Steps:

#### 1. Data Cleaning
- Removed irrelevant fields
- Handled missing values
- Standardized return percentages and expenses

#### 2. Descriptive Stats
- Analyzed distribution of returns, AUM, risk levels, fund age

#### 3. Normalization
- Applied `MinMaxScaler` to normalize numeric fields for scoring

#### 4. Scoring & Ranking
Calculated custom scores based on:
- 3-Year Return (higher = better)
- Expense Ratio (lower = better)
- Fund Age (moderate = better)
- Positive 1-Year Return

#### 5. Final Output
Extracted and saved the top 30 mutual fund schemes  
📄 [Download Top 30 Funds (Excel)](https://github.com/niravtrivedi23/Mutual-Fund-Analysis/blob/main/top_30_mutual_funds.xlsx)

---

## 📈 Power BI Dashboard

After filtering the data in Python and Excel, insights were visualized using Power BI.  
🔗 [Download PBIX File](https://github.com/niravtrivedi23/Mutual-Fund-Analysis/blob/main/Mutual%20Fund%20Dashboard.pbix)  
🖼️ [Dashboard Preview](https://github.com/niravtrivedi23/Mutual-Fund-Analysis/blob/main/Mutual%20Fund%20Dashboard%20.png)

### 🔍 Dashboard Features:

#### 🎛️ Filters:
- Fund Type, AMC, Risk, Sub-category, Fund Rating

#### 📊 Visuals:
- AUM distribution by fund type  
- SIP vs Lumpsum analysis  
- Expense Ratio comparison  
- Top-performing AMCs & fund managers  
- Donut charts for 3-year returns  
- Auto-generated insight cards

---

## 🔍 Investment Insights (Based on Dashboard)

| Category | Insight |
|----------|---------|
| 💼 Equity Fund AUM | ₹1.35M Cr – Highest among all fund types |
| 👤 Fund Manager | Vivek Sharma manages ₹7.3M Cr AUM |
| 💸 Lowest Expense Ratio | Index Funds – Avg. 0.26% |
| 🏦 Best 1-Year Return | Bank of India MF – 14.4% |
| 🔄 SIP Trends | Avg. ₹528.50/month |
| 📈 Long-Term Return | Equity – 37.84%, Hybrid – 14.25% |

---

## 🧠 Final Thoughts

This project demonstrates how combining **Python, Excel, and Power BI** enables data-driven investment decisions.  
It simplifies mutual fund selection based on return, cost, and performance consistency.

💡 **Invest smart, invest early – with the power of data.**

---

## 🧰 Tool Summary

| Tool     | Purpose |
|----------|---------|
| Python   | Data processing, scoring, ranking |
| Excel    | Formatting and validation |
| Power BI | Visualization and storytelling |

---



