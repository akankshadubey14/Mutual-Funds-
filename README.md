# 📊 Mutual Fund Analysis – Identifying Top 30 High-Return, Low-Risk Schemes

This project focuses on evaluating and selecting the **top 30 mutual fund schemes** that offer **high returns with minimal risk**, using Python for data analysis, Excel for preprocessing, and Power BI for dynamic visual reporting.

---

## 🛠️ Tools & Technologies Used

- **Python** (Pandas, Scikit-learn): Data wrangling, normalization, scoring  
- **Excel**: Data structuring, formatting, and initial validation  
- **Power BI**: Building interactive dashboards for insights

📁 **Dataset Size**: 2,500+ mutual fund schemes  
📌 **Goal**: Identify top performers based on return-risk-efficiency balance

---

## 🎯 Project Objective

To support investors in selecting mutual fund schemes with:
- Consistent long-term performance  
- Competitive expense ratios  
- Moderate risk exposure  
- Stable historical returns  

All findings are visually delivered through an **interactive Power BI dashboard**.

---

## 🐍 Python-Driven Analysis Workflow

### 🔹 Key Methodologies

#### 1. Data Cleaning
- Dropped non-essential fields  
- Imputed missing values  
- Standardized percentage formats  

#### 2. Exploratory Analysis
- Assessed return distributions, AUM trends, risk grades, and fund age

#### 3. Normalization
- Used `MinMaxScaler` to bring numeric features onto a comparable scale

#### 4. Scoring & Ranking
Developed a custom scoring system based on:
- 3-Year Return (positively weighted)  
- Expense Ratio (negatively weighted)  
- Fund Age (preferred mid-range)  
- 1-Year Positive Return flag

#### 5. Top 30 Selection
Extracted top-ranked mutual fund schemes for further visualization

---

## 📈 Power BI Dashboard Insights

Following Python-based filtering and Excel validations, Power BI was used to construct a comprehensive visual representation of the analysis.

### 🔧 Dashboard Features

**Filters:**
- Fund Category  
- AMC  
- Risk Grade  
- Sub-category  
- Fund Rating  

**Visuals:**
- AUM breakdown by fund type  
- SIP vs Lumpsum investment comparisons  
- Expense Ratio heatmap  
- Top AMC and Fund Manager performance  
- Donut charts for multi-year returns  
- Auto-generated insight cards

---

## 🔍 Key Investment Insights

| Category             | Insight                                 |
|----------------------|------------------------------------------|
| 💼 Equity Fund AUM    | ₹1.35M Cr – Highest among all fund types |
| 👤 Fund Manager       | Vivek Sharma manages ₹7.3M Cr AUM        |
| 💸 Expense Efficiency | Index Funds – Avg. 0.26% Expense Ratio   |
| 🏦 1-Year Return       | Bank of India MF – 14.4% Return          |
| 🔄 SIP Trends         | Avg. ₹528.50/month                       |
| 📈 Long-Term Returns  | Equity – 37.84%, Hybrid – 14.25%         |

---

## 🧠 Conclusion

This project demonstrates how the synergy of **Python**, **Excel**, and **Power BI** can power smart investment insights through rigorous analysis, effective filtering, and intuitive visualization.  
It empowers investors to confidently shortlist mutual funds that align with both financial goals and risk appetite.

**Investing is no longer guesswork—it's data-driven decision-making.**

---

## 🚀 Future Scope

- Integrate real-time data APIs (e.g., AMFI, Morningstar) for live fund updates  
- Expand the model to include Sharpe Ratio, Alpha, and Beta metrics  
- Add predictive modeling to forecast fund performance  
- Build a web-based application for user-level filtering and personalization

---

## 🧰 Tool Utilization Overview

| Tool     | Role                              |
|----------|-----------------------------------|
| Python   | Data cleansing, analysis, ranking |
| Excel    | Preprocessing, structuring        |
| Power BI | Visual storytelling and insights  |

---

> ⚠️ **Disclaimer:**  
> This project is for academic and portfolio purposes only. The mutual fund rankings and insights shared here are based on historical and synthetic data, and **should not be used for real-life financial or investment decisions**.
