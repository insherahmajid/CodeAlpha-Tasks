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
The final dataset is stored as: [books_page1_clean.csv](Datasets/books_page1_clean.csv)  
**Notebook:** [codealpha_webscraping.ipynb](Python/codealpha_webscraping.ipynb)
It contains **20 records**, each representing one book from Page 1.

---

## Ethical Considerations
BooksToScrape is a **public demo website** explicitly created for learning web scraping.  
No private or sensitive data was accessed.

---

## ✔ Task Status
Task 1 Completed Successfully (Page 1 Scraped)


