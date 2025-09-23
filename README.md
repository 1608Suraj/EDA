# 🚚 Logistics Companies Data Analysis (US & India)

## 🔹 Project Overview
This project focuses on **collecting, cleaning, and analyzing logistics company data** from the **United States** and **India**.  
The goal is to build a **clean, enriched dataset** by combining API-scraped and manually collected data, applying **EDA (Exploratory Data Analysis)**, and filling gaps using an **AI-powered model**.

---

## 📂 Dataset Details

### 1️⃣ `logistics.csv`
- Raw **US logistics companies data** collected via API.  
- Contains company details such as name, location, and industry.  
- Includes missing values and unstructured fields that required cleaning.  

### 2️⃣ `Indian_US_companies.csv`
- Final **cleaned and enriched dataset** of **Indian + US companies**.  
- Output after:
  - Data Cleaning  
  - EDA  
  - AI-based enrichment (Groq LLM)  

---

## 🧹 Data Cleaning, Enrichment & EDA Steps
1. **Data Collection**
   - US companies → API scraping  
   - Indian companies → Manual entry  

2. **Data Cleaning**
   - Removed duplicates  
   - Standardized company names, locations, and industry categories  
   - Handled inconsistent formatting
   - filter out some essential features 

3. **AI-Powered Enrichment**
   - Missing fields (e.g., city, state, industry) were **contextually filled using the Groq LLM API**  
   - The model inferred **likely values** based on available metadata and global business context  
   - Enhanced the dataset with **higher completeness and accuracy**  

4. **Exploratory Data Analysis (EDA)**
   - Checked distribution of companies across regions  
   - Compared **India vs US industry spread**  
   - Verified data consistency after enrichment  
