# CodeAlpha Internship TASK_1 Web Scraping  🕸️

## 📌 Project Overview
This Python project was developed as part of **Task 1 – Web Scraping** for the **CodeAlpha internship**. It automates the collection of remote job listings from **RemoteOK** across multiple categories, including **Development, Design, Marketing, Writing, and Sales**.

The scraped data includes **Job Title, Company Name, Location, Salary, and Job Link**, and is saved in a **professionally styled Excel file** ready for analysis or presentation.
---
## 🚀 Features
- Scrapes jobs from multiple RemoteOK categories  
- Extracts key information: Title, Company, Location, Salary, Link, and Category  
- Saves results in an Excel file with:
  - Colored headers and bold column titles  
  - Borders and alternating row colors  
  - Auto-fit columns and filters for easy sorting  

---
## 🛠️ Tech Stack
- **Python**  
- **requests** – to fetch HTML content  
- **BeautifulSoup** – to parse HTML and extract data  
- **pandas** – to manage and organize data  
- **openpyxl** – to style and format the Excel output  

---
## 📂 How to Run
1. Install dependencies:
   - pip install requests beautifulsoup4 pandas openpyxl

2. Run the scraper:
   - python jobs_scraper.py

3. Open the generated jobs_multi.xlsx file to view results.


