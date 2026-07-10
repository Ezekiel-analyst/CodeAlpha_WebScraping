CodeAlpha Web Scraping Task

 Task Overview

This project was completed as part of the CodeAlpha Data Analytics Internship (Task 1 — Web Scraping).
The goal was to extract data from a public website and create a structured dataset for further analysis.


🛠 Tools Used


Octoparse (No-code web scraping tool)
Microsoft Excel (Data cleaning and formatting)



🌐 Website Scraped

books.toscrape.com — A publicly available sandbox website for web scraping practice.


📦 Data Collected

The following fields were extracted:

ColumnDescriptionTitleName of the bookPricePrice of the book in GBP (£)


Total Records: 1,000 books across 50 pages
Pagination: Enabled to scrape all pages automatically



🔄 Process


Opened Octoparse and created a new scraping task
Pasted the URL: https://books.toscrape.com
Used Auto-detect to identify data fields (Title, Price)
Enabled pagination to scrape all 50 pages
Ran the task locally and exported data as CSV
Opened CSV in Excel and cleaned the price column (removed encoding characters)
Converted price to numeric format for analysis



📁 Files in This Repository

FileDescriptionbooks_data.csvRaw scraped dataset (1,000 rows)README.mdProject documentation


💡 Key Findings


Successfully scraped 1,000 book listings from 50 pages
Price range: £10.00 – £59.99
Average book price: £35.07
Data was clean with no missing values after formatting



👨‍💻 Author

Ayobami Oni Ezekiel
Data Analytics Intern — CodeAlpha
LinkedIn | GitHub
