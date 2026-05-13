# E-Commerce Purchase Behaviour Dashboard
### A Data-Driven Analysis of Online Buying Patterns Among College Girl Students in Amravati

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Survey](https://img.shields.io/badge/Primary%20Survey-n%3D100-blue)
![Chi-Square](https://img.shields.io/badge/Chi--Square-p%3D0.008-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## Dashboard Preview
![Power BI Dashboard](https://github.com/neharahate07/E-Commerce-Purchase-Behaviour-Analysis/blob/main/Dashboard%20Image.png)

---

## Project Overview

This is an **end-to-end MBA dissertation project** that uses primary survey data (n=100) to analyse the online purchase behaviour of college girl students in Amravati for **fashion and beauty products**. The analysis includes descriptive statistics, Likert-scale scoring, Chi-square hypothesis testing, and an interactive Power BI dashboard.

> **Dissertation Title:** *"A Data-Driven Analysis of E-Commerce Purchase Behaviour for Fashion and Beauty Products Among College Girl Students in Amravati"*
>
> **Institution:** Sipna College of Engineering & Technology, Amravati, Maharashtra
> **Program:** MBA (Business Analytics) | Batch 2024–26

---

## Research Objectives

- Analyse the online shopping behaviour of college girl students in Amravati for fashion and beauty products
- Identify key factors influencing purchase decisions — price, convenience, trust, peer influence, and digital marketing
- Assess the role of technology and social media platforms in shaping consumer preferences
- Identify challenges faced by students and suggest strategies to improve their shopping experience

---

## Hypothesis Tested

| | Hypothesis |
|---|---|
| **H₀ (Null)** | There is no significant relationship between influencing factors (price, brand, convenience, peer influence) and online purchase behaviour |
| **H₁ (Alternative)** | There is a significant relationship between influencing factors and online purchase behaviour |

**Result:** χ² = 17.2, df = 6, **p-value = 0.008 < 0.05** → **H₁ Accepted** ✅

---

## Dashboard Visuals (Power BI)

| # | Visual | Data Source | Insight |
|---|--------|------------|---------|
| 1 | KPI Cards | Survey_Raw_Data | Respondents, Avg Spend, Satisfaction %, Influencer Impact |
| 2 | Horizontal Bar | Likert_Scores | Weighted means of all 13 influence factors |
| 3 | Donut Chart | Summary_Tables | Platform preference — Meesho leads at 26% |
| 4 | Clustered Bar | Survey_Raw_Data | Monthly spend by age group and product category |
| 5 | Chi-Square Table | Chi_Square_Results | p-values and significance for each variable pair |
| 6 | Stacked Bar | Summary_Tables | Issues faced by respondents |
| 7 | Pie Chart | Summary_Tables | Decision influence sources |
| 8 | Slicers | All Sheets | Filter by Age Group, Year of Study, Platform, Category |

---

## Key Findings

### Demographics
- **53%** of respondents are aged 18–20; **93%** fall in the 18–23 age range
- **55%** have a monthly allowance above ₹3,000 — real purchasing power
- **84%** shop online frequently or occasionally — zero respondents reported "Never"

### Platform Preference *(Multi-select, n=250 responses)*
| Platform | Responses | Share |
|----------|-----------|-------|
| Meesho | 65 | 26% |
| Myntra | 48 | 20% |
| Nykaa | 41 | 16% |
| Flipkart | 35 | 14% |
| Ajio | 31 | 13% |
| Amazon | 30 | 11% |

### Purchase Drivers — Weighted Mean Scores (1–5 scale)
| Factor | Weighted Mean | Rank |
|--------|:---:|:---:|
| Return / Refund Policy | **4.25** | 🥇 1st |
| Influencer Impact | **4.23** | 🥈 2nd |
| Discount Influence | **4.23** | 🥈 2nd |
| Price Comparison | **4.15** | 4th |
| Saves Time & Effort | **4.15** | 4th |
| Reviews & Ratings | **4.09** | 6th |
| Easier Than Offline | **4.03** | 7th |
| Product Quality Satisfaction | **3.82** | 8th |
| Payment Security | **3.74** | 9th |
| Refund Policy Awareness | **3.73** | 10th |
| Trust in Platforms | **3.66** | 11th |
| Brand Preference | **3.64** | 12th |
| UX / App Interface | **3.61** | 13th |

### Decision Influence Sources
- **Online Reviews** → 31% *(single highest)*
- **Friends + Social Media Influencers** → 42% combined
- **Own Decision** → only 16%
- Combined social proof (reviews + friends + influencers) = **73% of purchase decisions**

### Challenges Faced
- Product not as described → **24%** (top pain point)
- Refund issues → **17%**
- Payment failures → **15%**
- Wrong size/colour → **13%**
- Delivery delays → **12%**
- **Zero respondents reported "No issues"**

### Satisfaction
- **77%** are satisfied or very satisfied overall
- **85%** say return/refund policies boost their confidence
- **82%** rely on reviews and ratings before purchasing

---

## Chi-Square Test Results

| Variable Pair | χ² | df | p-value | Result |
|---|:---:|:---:|:---:|:---:|
| Overall Factors vs Purchase Behaviour | 17.2 | 6 | **0.008** | ✅ Significant |
| Discount Influence vs Purchase | 8.4 | 2 | 0.015 | ✅ Significant |
| Influencer Impact vs Purchase | 9.1 | 2 | 0.011 | ✅ Significant |
| Return Policy vs Purchase | 7.8 | 2 | 0.020 | ✅ Significant |
| Brand Preference vs Purchase | 6.2 | 2 | 0.045 | ✅ Significant |
| Platform UX vs Purchase | 4.1 | 2 | 0.129 | ❌ Not Significant |
| Trust vs Purchase | 5.9 | 2 | 0.052 | ⚠️ Borderline |

*Significance level α = 0.05*

---

## Business Recommendations

**1. Prioritise Influencer-Led Micro-Campaigns in Tier-II Cities**
Social media influencers and friends together drive 42% of decisions. Partner with Amravati-based student content creators on Instagram and YouTube for authentic, relatable promotions.

**2. Make Return Policies Visible and Hassle-Free**
Return/refund policy has the highest weighted mean (4.25/5). Display it prominently on every product page — it is the single most powerful trust signal for this segment.

**3. Fix Product Accuracy Before Chasing Growth**
"Product not as described" is the #1 issue (24%). Accurate imagery, standardised sizing charts, and shade-matched cosmetic photography directly improve satisfaction.

**4. Expand Payment Options — UPI, BNPL, EMI**
"More payment options" is the top-requested platform improvement (31%). BNPL and EMI options for orders above ₹1,000 will unlock the high-allowance segment.

**5. Build Review Ecosystems Around Student Buyers**
Online reviews are the single most trusted source (31%). Incentivising photo and video reviews from verified student buyers creates compounding social proof.

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Google Forms** | Primary data collection |
| **Microsoft Excel** | Data entry, cleaning, pivot tables, frequency analysis |
| **Power BI Desktop** | Interactive dashboard, DAX measures, slicers |
| **Power Query** | Data transformation and normalisation |
| **Python (Pandas, NumPy, Matplotlib, SciPy)** | EDA, Chi-square testing, visualisation |
| **DAX** | Custom KPI measures in Power BI |

---

## Repository Structure

```
Ecommerce-purchase-behaviour-amravati
 ┣ data
 ┃ ┣ Neha_PowerBI_Dataset.xlsx      ← Power BI ready: Raw data + Summary + Likert + Chi-Square + Setup Guide
 ┃ ┗ data_dictionary.md             ← Column descriptions and value labels
 ┣ analysis
 ┃ ┣ eda_analysis.ipynb             ← Python EDA notebook
 ┃ ┗ chi_square_tests.ipynb         ← Hypothesis testing with scipy
 ┣ dashboard
 ┃ ┣ purchase_behaviour.pbix        ← Power BI dashboard file
 ┃ ┗ dashboard_screenshot.png       ← Dashboard preview
 ┣ dissertation
 ┃ ┗ Dissertation_Report.pdf        ← Full academic report
 ┗ README.md
```

---

## How to Use This Project

### Open the Power BI Dashboard
```
1. Download Power BI Desktop (free) → https://powerbi.microsoft.com/desktop/
2. Clone: git clone https://github.com/neharahate/ecommerce-purchase-behaviour-amravati
3. Open: dashboard/purchase_behaviour.pbix
4. Data loads from Neha_PowerBI_Dataset.xlsx automatically
5. Use slicers to filter by Age Group, Year of Study, Platform, Category
```

### Reproduce the Python Analysis
```bash
git clone https://github.com/neharahate/ecommerce-purchase-behaviour-amravati
cd ecommerce-purchase-behaviour-amravati
pip install pandas numpy matplotlib seaborn scipy openpyxl jupyter
jupyter notebook analysis/
```

### Key DAX Measures
```dax
-- Average Monthly Spend
AvgSpend = AVERAGE(Survey_Raw_Data[Monthly_Spend_INR])

-- Influencer High Impact %
InfluencerHighImpact% =
DIVIDE(
    COUNTROWS(FILTER(Survey_Raw_Data, Survey_Raw_Data[Influencer_Impact] >= 4)),
    COUNTROWS(Survey_Raw_Data)
) * 100

-- Satisfaction Rate
SatisfactionRate% =
DIVIDE(
    COUNTROWS(FILTER(Survey_Raw_Data, Survey_Raw_Data[Overall_Satisfaction] >= 4)),
    COUNTROWS(Survey_Raw_Data)
) * 100
```

---

## Research Methodology

| Parameter | Detail |
|-----------|--------|
| **Research Design** | Descriptive + Analytical |
| **Data Type** | Primary (survey) + Secondary (literature) |
| **Sample Size** | n = 100 female college students |
| **Sampling Method** | Convenience + Purposive (Non-probability) |
| **Target Population** | College girl students in Amravati (age 15–24) |
| **Data Collection** | Structured questionnaire — Google Forms + Offline |
| **Scale** | Likert 1–5 for attitudinal variables |
| **Statistical Test** | Chi-Square Test of Independence (α = 0.05) |
| **Study Period** | 2024–25 |

---

## Theoretical Framework

1. **Hedonic & Utilitarian Motivation Theory** — Dual purchase motivations: enjoyment vs. practicality
2. **Theory of Planned Behaviour (TPB)** — Attitude, subjective norms, and perceived behavioural control
3. **Social Influence & Social Comparison Theory** — Peer and influencer-driven aspirational buying
4. **Trust & Perceived Risk Framework** — How platform credibility reduces purchase hesitation

---

## About the Researcher

**Neha Rahate**
MBA (Business Analytics) | Sipna College of Engineering & Technology, Amravati
**CGPA: 8.98** | Batch: 2024–26

**Skills:** Power BI · Excel · Python (Pandas, NumPy, Matplotlib) · SQL · Tableau · SAS
**Certifications:** Data Visualization — TATA Forage | Data Analytics — Deloitte Forage | Power BI Skill Course | Base SAS — SAS India

📧 neharahate077@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/neha-rahate-179863246)

---

## License

Shared for academic and portfolio purposes. Please credit the author when referencing findings.

---

*MBA Dissertation — Sipna College of Engineering & Technology, Amravati, Maharashtra*


