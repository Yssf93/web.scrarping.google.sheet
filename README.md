# Web Scraping → Google Sheets Automation
Python automation script that scrapes book data from:
https://books.toscrape.com

and sends it automatically to Google Sheets.

## 🚀 Features
- Scrapes multiple pages (pagination)
- Extracts product data automatically
- Sends data directly to Google Sheets
- Can be exported to CSV for backup

## 📊 Data Fields
- Title
- Price
- Availability (Stock)
- Rating
- Category
- Product URL

## 🛠️ Tech Stack
- Python
- Requests
- BeautifulSoup
- Pandas
- Google Sheets API (gspread)

## ▶ How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt
