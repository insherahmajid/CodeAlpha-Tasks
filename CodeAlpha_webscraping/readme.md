# Task 1 – Web Scraping (BooksToScrape)

## Overview
This task involves scraping book data from **https://books.toscrape.com/** — a public demo website designed specifically for practicing web scraping.

For this task, I scraped **only Page 1**, which contains **20 books**.

---

## Website Scraped
**Books to Scrape – Home Page**  
URL: https://books.toscrape.com/  
This page lists 20 book entries, all of which were successfully scraped.

---

## 📄 Data Extracted
For each book, the following information was collected:

- Title  
- Price  
- Availability  
- Star Rating  
- Product URL  
- Category (from breadcrumbs)

---

## 🛠 Tools & Libraries Used
- Python  
- Requests  
- BeautifulSoup (bs4)  
- Pandas  

---

## 🧹 Cleaning & Processing
- Cleaned string values for title, availability, and category  
- Converted price to numeric format  
- Extracted rating as text  
- Created a structured DataFrame  
- Exported the final dataset as CSV

---

##  Output 
The final dataset is stored as: [books_page1_clean.csv](CodeAlpha_webscraping/books_page1_clean.csv)  
**Notebook:** [codealpha_webscraping.ipynb](CodeAlpha_webscraping/codealpha_webscraping.ipynb)
**Vedio Explanation**[WATCH HERE](https://drive.google.com/file/d/1PNX-tVDWoUzP-Ka62EVYtr_B8UPQqaA3/view?usp=sharing)
It contains **20 records**, each representing one book from Page 1.
**LinkedIn Post Link**[Check Here](https://www.linkedin.com/posts/insherah-majid-146496317_codealpha-internship-task-1-completed-completed-activity-7403735463036989440-GdSN?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFBW4kYBpa2mBkrH4-NH-AnzPdSnKTptRTo)

---

## Ethical Considerations
BooksToScrape is a **public demo website** explicitly created for learning web scraping.  
No private or sensitive data was accessed.

---

## ✔ Task Status
Task 1 Completed Successfully (Page 1 Scraped)


