# 📊 San Francisco County Insights Dashboard: Comprehensive Zip Code Analysis

This project analyzes and visualizes socioeconomic and demographic data across San Francisco zip codes to generate a **Comprehensive Regional Score** using Tableau.  

## 🔍 Methodology
- **Normalization**: Converted all variables to a 0–10 scale.
  - Positive indicators (education, income, employment, population): higher = better.
  - Negative indicators (crime rate, housing prices): higher = worse.
- **Weighting**:  
  - Population (10%)  
  - Education (20%)  
  - Employment Rate (20%)  
  - Median Household Income (20%)  
  - Housing Prices (10%)  
  - Crime Rate (20%)  
- **Comprehensive Score**: Weighted sum of normalized scores.

## 📂 Files in this Repository
- `Shivakumar_CVA_Project_02.pdf` – Full project report.
- `CVA_PROJECT_02.twb` – Tableau workbook file.

## 🌐 Interactive Dashboard
👉 [San Francisco County Insights Dashboard](https://public.tableau.com/app/profile/shivakumar.hassan.lokesh/viz/SanFranciscoCountyInsightsDashboardComprehensiveZipCodeAnalysis/Dashboard1)

## 📊 Data Sources
- U.S. Census Bureau – Income & Poverty Data  
- CrimeGrade.org – Crime Data & Safety Ratings  
- Zillow – Housing Prices  

---

👤 **Author**: Shivakumar Hassan Lokesh  
📚 Course: IE6600 Computation and Visualization (Fall 2024)
