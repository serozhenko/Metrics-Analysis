# Online Store Analytics Project

This project involves building analytics for an online store using three tools: **SQL**, **Python**, and **Tableau**.

---

## Project Goal
- Demonstrate skills in extracting data from a database using **SQL**  
- Demonstrate skills in exploratory and statistical analysis in **Python**  
- Demonstrate skills in building dashboards in **Tableau**

---

## Final Result
- Jupyter Notebook with:
  - Data loading from the database
  - Exploratory and statistical analysis in Python  
- Dashboard in **Tableau Public**

---

## Project Implementation Plan
1. Using a **Python script**, we connected to the database in **Google BigQuery (DA dataset)**.  
2. Based on the available tables, we created a dataset with the following fields:
   - `order date`
   - `session ID`
   - `continent`
   - `country`
   - `device`
   - `browser`
   - `device model name`
   - `operating system`
   - `browser language`
   - `traffic source information`
   - `traffic channel`
   - `registered user ID`
   - `whether the user confirmed their email`
   - `whether the user subscribed to the newsletter`
   - `product category`
   - `product name`
   - `price`
   - `short product description`

3. Using this dataset, we:
   - Obtained key sales metrics for the online store  
   - Built summary tables  
   - Analyzed sales dynamics by category, country, and continent  

---

## Statistical Analysis
We performed:
- **Correlation analysis**  
- **Group comparison tests**  

using the `scipy.stats` library in Python to evaluate statistical significance and identify meaningful results.

---

## Tools & Technologies
- **SQL** (Google BigQuery)  
- **Python** (Pandas, NumPy, SciPy, Matplotlib, Seaborn)  
- **Tableau Public**

---

## Dashboard
[View Tableau Dashboard](https://public.tableau.com/app/profile/viktoriia.serozhenko6318/viz/Project1_17566774474770/Project1?publish=yes) 

