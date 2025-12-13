# 📊 Task 2 – Exploratory Data Analysis (EDA)
**Internship:** CodeAlpha – Data Analytics  
**Author:** Insherah Majid  

---

🔍 Overview

Task 2 focuses on performing Exploratory Data Analysis (EDA) on the Amazon product reviews dataset.
The objective is to understand the dataset structure, clean and prepare the data, identify trends and patterns, test hypotheses, and derive insights about customer behavior.

This task provides the analytical foundation for Task 3 (Visualization) and Task 4 (Sentiment Analysis).

📁 Dataset Summary

The dataset includes the following key columns

rating – Customer rating (1–5)

review_text – Customer review content

review_date – Date of review

votes – Helpful vote count

summary 

##  Data Cleaning Performed

Verified missing values:

No missing values in votes

One missing value in review_text, replaced with "no review text"

Standardized text columns

Converted review_date into datetime format

Removed duplicate reviews

Ensured numeric columns were properly typed

 ## Feature Engineering (Word Count Analysis)

To enable deeper analysis, additional features were engineered:

review_length – Number of words in each review

summary_length – Length of review summary

review_year – Year extracted from review date

📌 Word count analysis converts unstructured text into numerical form, enabling correlation analysis and hypothesis testing.

📊 Exploratory Analysis Conducted
1. Univariate Analysis

Distribution of ratings

Distribution of helpful votes

Distribution of review lengths

Category frequency

2. Bivariate Analysis

Review length vs rating

Helpful votes vs rating

Category vs rating

3. Time-Based Trends

Number of reviews over time

Average rating per year

4. Correlation Analysis

Correlation between:

rating and review length

review length and helpful votes

rating and helpful votes

Visualized using correlation matrices and heatmaps

📌 Correlation analysis helps validate relationships observed during exploratory analysis and supports hypothesis testing.

5. Simple Text Analysis

(Sentiment analysis is intentionally excluded — covered in Task 4)

Extracted frequently occurring words

Removed basic stopwords

Visualized top 20 most common words using bar charts

🧪 Hypotheses Tested

Lower ratings have longer reviews

Partially supported

5-star reviews receive more helpful votes

Mixed results with observable patterns

Average rating remains stable over time

Supported by yearly trend analysis

Each hypothesis was tested using EDA techniques, visualizations, and correlation analysis, aligning with CodeAlpha Task-2 requirements.

📈 Visualizations Included

The notebook contains multiple visualizations such as:

Rating distribution plot

Helpful vote distribution

Review length distribution

Boxplots (rating vs review length, rating vs votes)

Category-wise rating analysis

Year-wise review trends

Word frequency bar chart

📄 Files in This Folder

[Eda.ipynb](Eda.ipynb) – Complete exploratory data analysis notebook

📝 Key Insights

Most customers provide positive ratings (5 stars)

Negative reviews tend to be longer and more descriptive

Review length shows a positive relationship with helpful votes

Only a small subset of reviews receives high engagement

Review volume displays time-based variation

Common themes in reviews focus on:

product quality

pricing

performance

🚀 Conclusion

This EDA task successfully explores the dataset, validates assumptions through hypothesis testing, and uncovers meaningful trends.

The insights generated here form a solid base for:

Task 3 – Data Visualization

Task 4 – Sentiment Analysis

🔗 Connect

LinkedIn: https://www.linkedin.com/in/insherah-majid-146496317/





