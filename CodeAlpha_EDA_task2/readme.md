# 📊 Task 2 – Exploratory Data Analysis (EDA)
**Internship:** CodeAlpha – Data Analytics  
**Author:** Insherah Majid  

---

## 🔍 Overview
Task 2 focuses on performing **Exploratory Data Analysis (EDA)** on the Amazon product reviews dataset.  
The objective is to understand the dataset structure, clean and prepare the data, identify trends and patterns, test hypotheses, and derive insights about customer behavior.

This task provides the analytical foundation for Task 3 (Visualization) and Task 4 (Sentiment Analysis).

---

## 📁 Dataset Summary
The dataset includes the following key columns:

- **product_name** – Name of the product  
- **category** – Product category  
- **rating** – Customer rating (1–5)  
- **review_text** – Customer review content  
- **review_date** – Date of review  
- **votes** – Helpful vote count  
- **price** – Product price  

---

## 🧹 Data Cleaning Performed

- Verified missing values:  
  - **No missing values in `votes`**  
  - **One missing value in `review_text`**, replaced with `"no review text"`  
- Standardized text columns  
- Converted `review_date` into datetime format  
- Removed duplicate reviews  
- Ensured numeric columns were properly typed  
- Added new engineered features:  
  - **review_length**  
  - **summary_length**  
  - **review_year**  

---

## 📊 Exploratory Analysis Conducted

### **1. Univariate Analysis**
- Distribution of ratings  
- Distribution of helpful votes  
- Distribution of review lengths  
- Category frequency  

### **2. Bivariate Analysis**
- Review length vs rating  
- Helpful votes vs rating  
- Category vs rating  

### **3. Time-Based Trends**
- Number of reviews over time  
- Average rating per year  

### **4. Simple Text Analysis**  
(Without sentiment — sentiment belongs to Task 4)
- Extracted most frequent words from review text  
- Cleaned basic stopwords  
- Visualized top 20 word frequencies  

---

## 🧪 Hypotheses Tested

1. **Lower ratings have longer reviews**  
   - Partially supported  

2. **5-star reviews receive more helpful votes**  
   - Mixed results but visible pattern  

3. **Average rating remains stable over time**  
   - Supported by yearly trend  

---

## 📈 Visualizations Included
The notebook contains multiple visualizations such as:

- Rating distribution plot  
- Helpful vote distribution  
- Review length analysis  
- Boxplots (rating vs review length, rating vs votes)  
- Category distribution  
- Yearly review trends  
- Word frequency bar chart  
---

## 📄 Files in This Folder

- **Eda.ipynb**[Eda.ipynb](Eda.ipynb) – Complete exploratory analysis  
- **Task2_vedio link**-  


---

## 📝 Key Insights

- Most customers provide **positive ratings** (4–5 stars)  
- Negative reviews tend to be **longer**, supporting the hypothesis  
- Only a small group of reviews receive high helpful-vote counts  
- Review volume shows **seasonal variation**  
- Common text patterns indicate customers care most about:  
  - product quality  
  - price  
  - performance  

---

## 🚀 Conclusion
The EDA provides a strong understanding of the dataset and prepares the foundation for:

- **Task 3** – Data visualization  
- **Task 4** – Sentiment analysis  

This structured analysis will help uncover deeper customer sentiment and behavioral trends in the upcoming tasks.

---

## 🔗 Connect
**LinkedIn:** https://www.linkedin.com/in/insherah-majid-146496317/ 



