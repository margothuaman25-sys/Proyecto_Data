Markdown
# 🚀 InsightReach: Market Intelligence & Recommendation Engine
### *Data-Driven Strategy for the US Restaurant Industry*

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-150458?style=for-the-badge&logo=pandas)
![Yelp API](https://img.shields.io/badge/Yelp_API-External_Data-FF1A1A?style=for-the-badge&logo=yelp)

## 🎯 Business Problem
**InsightReach** needed to transform raw data into strategic decisions. The goal: How can we identify the best restaurants in specific markets (like Miami) and connect them with the most profitable customer profiles?

---

## 🛠️ Data Pipeline (Executive Summary)

### 📈 1. From 30,000 Records to Strategic Insights (EDA)
We didn't just clean data; we looked for gold.
* **Total Integrity**: Validated 30k records ensuring 0% nulls in critical income and age variables.
* **Miami Focus**: Identified that while Chicago has volume, **Miami has superior customer retention rates**[cite: 1].
* **Feature Engineering**: Created `estrato_preferencia` to segment specific high-value niches (e.g., Luxury clients who love Italian cuisine)[cite: 1].

### 🔌 2. Market Intelligence (Yelp API & ETL)
Enriched internal data with real-world market insights[cite: 1].
* **Scalability**: Implemented pagination to extract **427 detailed restaurants** in Miami[cite: 1].
* **Resilience**: Applied **imputation techniques** to save geographic data that others would discard[cite: 1].
* **Normalization**: Translated technical data into business categories: *Low, Medium, High,* and *Very High*[cite: 1].

### 🧠 3. Recommendation Engine (Bayesian Ranking)
* **Strategic Inner Join**: Merged customer tastes with real offerings to guarantee **zero-error recommendations**[cite: 1].
* **Weighted Rating Formula**: Implemented Bayesian statistics to identify "Elite" venues, prioritizing those with high review volume over empty star ratings[cite: 1].

---

## 📂 Repository Structure
* 📂 [`EDA_US_Restaurants_Analysis.ipynb`](./EDA_US_Restaurants_Analysis.ipynb): Economic analysis and strategic segmentation[cite: 1].
* 📂 [`API_Implementation_InsightReach_Project.ipynb`](./API_Implementation_InsightReach_Project.ipynb): ETL process and API integration[cite: 1].

## 👤 Contact
**[Tu Nombre]**  
*Economist | Data Scientist | Business Intelligence*  
[LinkedIn](TU_URL_DE_LINKEDIN) | [Portfolio](TU_URL_DE_GITHUB)
