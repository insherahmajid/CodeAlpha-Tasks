#  Amazon Electronics Reviews – Data Visualization Dashboard  
**CodeAlpha Internship | Task 3 – Data Visualization**

---

##  Project Overview
This project focuses on building an **interactive data visualization dashboard** to analyze customer review behavior for **Amazon Electronics products**.

The dataset used in this task was **cleaned, processed, and enhanced in Task 2**, where additional analytical columns were created.  
Using this refined dataset, the objective of Task 3 is to convert data into **clear, interactive, and actionable visual insights** using **Power BI**.

---

##  Data Preparation (Task 2 Reference)
Before creating the dashboard, the dataset underwent **data cleaning and feature engineering** in **Task 2**:

### ✔ Cleaning Performed
- Removed missing and inconsistent values
- Standardized date fields (review year & month)
- Ensured numerical consistency in ratings and votes

###  New Columns Added in Task 2
- **Review Length** (word count of review text)
- **Summary Length** (word count of review summary)

These engineered features were crucial for:
- Review length distribution analysis
- Rating vs engagement comparisons
- Advanced visual segmentation in the dashboard

---

##  Objectives (Task 3)
- Build an **interactive Power BI dashboard**
- Visualize **review trends over time**
- Analyze **customer rating distribution**
- Understand **review length patterns**
- Study the relationship between **ratings and helpful votes**
- Enable filtering by **year, month, and rating**

---

## 📂 Dataset Description
The final dataset used for visualization contains the following key fields:

- `review_year`
- `review_month`
- `overall` (rating)
- `review_length`
- `summary_length`
- `review_len_cat`
- `vote` (helpful votes)
- `reviewText`
- **Review Length Category**  
  - Short Reviews  
  - Medium Reviews  
  - Long Reviews
    (This column was added in power bi)
This dataset represents **post-cleaning and feature-enhanced data from Task 2**.

---

##  Tools & Technologies Used
- **Power BI Desktop** – Dashboard creation & interactivity  
- **Python** – Data cleaning & feature engineering (Task 2)  
- **Pandas & NumPy** – Data manipulation  
- **Matplotlib & Seaborn** – Exploratory analysis  
- **DAX** – KPI measures and calculations  

---

## 📊 Dashboard Components

### 🔹 Key Performance Indicators (KPIs)
- **Total Reviews**
- **Average Rating**
- **Average Helpful Votes**
- **Average Review Length**
- **Average Summary Length**

---

### 🔹 Visualizations Included
- **Customer Rating Distribution**  
- **Distribution of Reviews by Review Length Category**
- **Review Volume Trend Over Time**
- **Helpful Votes and Review Length by Rating**

---

### 🔹 Interactive Filters (Slicers)
- **Review Year**
- **Review Month**
- **Ratings**

These slicers allow dynamic, drill-down analysis across time and rating levels.

---

## Key Insights
- Medium-length reviews dominate customer feedback
- Higher ratings tend to receive more helpful votes
- Review volume grew steadily until mid-2010s and then declined
- Ratings are relatively evenly distributed across products

---

##  Dashboard Design Principles
- Clean and consistent theme
- KPI-first layout for quick insights
- Minimal clutter with clear labeling
- Optimized for both analysis and presentation

---
Files
-  **Power BI File:** [CodeAlpha_Data_Visualization.pbix](CodeAlpha_Data_Visualization.pbix)
 - **Dashboard Report (PDF):** [CodeAlpha_Data_Visualization.pdf](CodeAlpha_Data_Visualization.pdf)  
-**Dashboard Preview:**  
 <p align="center">
    <img src="Screenshot(101).png"
     </p>
   
---



## 👩‍💻 Author
**Insherah Majid**  
Data Analytics Intern – CodeAlpha  

linkedIn:(www.linkedin.com/in/insherah-majid-146496317)
---

⭐ If you find this project useful, feel free to star the repository!

