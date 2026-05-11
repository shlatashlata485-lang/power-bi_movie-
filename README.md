# Movie Industry Analysis Dashboard 🎬

## Project Overview
This Power BI dashboard provides a deep dive into movie industry trends, analyzing what makes a movie successful in terms of engagement, ratings, and revenue.

---

## 📊 Dashboard Preview

---<p align="center">
  <img src="اسم_الصورة_الجديد.png" width="850">
</p>

## 💡 Key Business Insights
Based on the data analysis, here are the main findings:

* **Audience Engagement:** Movies with an **(18+) rating** are the most effective at driving audience interaction and voting. 
    * *Recommendation:* Focus on providing more mature-rated content to maintain current engagement levels.
* **The "Success" Runtime:** High-rated movies tend to be longer, with an average duration of **2.5 hours**.
* **The Golden Era:** Movies produced in the **2000s** hold the highest average ratings compared to other decades.
    * *Recommendation:* Revive these classics through "Must-Watch" lists to attract new subscribers.
* **Marketing Opportunity:** Modern movies (Post-2010) show a **90% promotion success rate**, suggesting that increased marketing spend in this category yields high returns.

---

## 🛠️ Technical Workflow

### 1. Data Cleaning (Power Query)
* Standardized movie genres and handled missing values in revenue data.
* Performed data transformation to categorize movies by decades.
* Cleaned and formatted the "Runtime" and "Rating" columns for accurate analysis.

### 2. Data Modeling & DAX
Used advanced DAX formulas to calculate key metrics:
* **Average Voting Rate:** Created measures to track engagement levels across different categories.
* **Success Ratio:** Built a logic to identify the 90% success rate for modern productions.
* **Era Comparison:** Used time-intelligence concepts to compare the performance of the 2000s era vs. others.

---

## 🚀 How to view the project
1. Download the `.pbix` file from this repository.
2. Open it using **Power BI Desktop**.
3. You can also find the raw data in the `movies.csv` file.
٤.
