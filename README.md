# MIS_311
#  Cost of Living Dataset Analysis

This repository presents an analysis of the **Cost of Living** dataset, which provides insight into income levels and essential living expenses across various countries and regions from **2000 to 2023**. The analysis covers data cleaning, descriptive statistics, and key economic insights.

---

##  1. Dataset Overview

The **Cost of Living** dataset offers a comprehensive look at how **average monthly income** and **cost of living** vary across different countries and time periods. It allows for cross-country and regional comparison of affordability and financial stability.

- **Dimensions:** 202 rows × 5 columns

###  Column Descriptions

<img width="652" height="487" alt="{C32D3DDF-7136-4407-81D1-C03EDD13A6A4}" src="https://github.com/user-attachments/assets/9560c8f5-b60e-4e04-97cb-a715845e8ce2" />


> ℹ️ **Data Source**:  
> While not explicitly cited, the dataset’s structure suggests it is compiled from reputable sources such as the **World Bank**, **IMF**, **ILO**, and **Numbeo**. These organizations are known for publishing standardized economic data, and the dataset likely draws from a mix of **official statistics and crowd-sourced insights**.

---

##  2. Data Cleaning

<img width="751" height="153" alt="{9912AD21-C065-4F18-B1BF-8515859B88C8}" src="https://github.com/user-attachments/assets/0c6c5b4f-9842-4f0c-93be-bba2085f5e3c" />


###  Duplicate Records
- **Issue:** 2 duplicate entries were found.
- **Action:** Removed using the “Remove Duplicates” function.
- **Result:** Dataset reduced to **200 unique country-year records**.

>  This ensures that each record reflects a distinct and accurate observation without biasing the analysis.

###  Missing Values

<img width="752" height="83" alt="{2D1CD998-04F0-4B41-9DE9-3BD41431A237}" src="https://github.com/user-attachments/assets/b363e5bb-7c73-45a9-b2f2-d855be655769" />


#### ➤ `Average_Monthly_Income`
- **Rows Affected:** 160 and 176  
- **Solution:** Imputed using the **median**, which is more robust against outliers compared to the mean.

  <img width="747" height="78" alt="{E1B2F90C-202E-4FC7-9E44-B2B8AC150275}" src="https://github.com/user-attachments/assets/8c8be4ef-8bc6-4fba-9ba0-7d94eded71ec" />

#### ➤ `Region`
- **Rows Affected:** 26 and 38  
- **Fix:** Verified and updated based on known country classification.  
  - Example: **Mexico** was correctly assigned to **North America**.

> 🛠️ These steps enhanced the **completeness, accuracy, and consistency** of the dataset.

---

##  3. Descriptive Statistics

<img width="751" height="290" alt="{079BEB9B-7F2A-4F24-8C10-AC3D0399CA23}" src="https://github.com/user-attachments/assets/797f3b43-8fc5-4748-9d4b-73366ed87cf0" />


> 📌 High standard deviations indicate **significant variation** in income and cost of living across countries—highlighting economic diversity worldwide.

---

##  4. Key Insights

### 🔹 Insight 1: Weak Correlation Between Income and Living Costs

<img width="927" height="353" alt="{B12412C3-7B3C-4BEE-84F9-37127307467E}" src="https://github.com/user-attachments/assets/a3e2b090-a623-4e08-8fab-78ecf0979104" />

- A **scatter plot** of income vs. cost of living reveals **no strong linear relationship**.
- Some nations with **high living costs** do **not necessarily** offer high incomes.
- Conversely, some countries with **low costs** show relatively **high income levels**.

> 🧠 This suggests that **income and expenses are influenced by separate economic forces** in different countries.

---

### 🔹 Insight 2: Regional Financial Disparities

<img width="755" height="376" alt="{B09630EB-9871-42D9-9A7A-7A80C09EE364}" src="https://github.com/user-attachments/assets/82324e7e-bf0f-4852-959d-6df940dd64b2" />

- A **bar chart** comparing regional totals shows:
  - **Europe** and **Asia** lead in overall income and expenses, reflecting **high economic activity**.
  - **North America** shows a **smaller gap** between income and living costs, hinting at **tighter financial margins**.

> 🌎 These differences underscore how **regional economic structures and living standards** influence financial stability and potential savings.

---

## ✅ Conclusion

The **Cost of Living** dataset provides meaningful insights into **global economic conditions** by examining the balance between income and expenses. Through careful data cleaning, statistical analysis, and visualization, we can identify patterns of inequality, financial health, and affordability across the world.

---


