# 📊 Data Acquisition Automation (Web Scraping + Excel Processing)

## 📌 Description
This project is a Python automation tool that extracts product data from a web platform using Selenium, processes it, and generates structured Excel reports.

It reads input IDs from an Excel file, retrieves corresponding data from a website, cleans and transforms it, and outputs a fully formatted Excel report with multiple sheets.

---

## ⚙️ Features
- Automated browser interaction using Selenium
- Reads input data from Excel (`Input File.xlsx`)
- Extracts structured data from web tables
- Cleans and transforms data using Pandas
- Generates final Excel report (`Output.xlsx`)
- Handles missing data and logs failed IDs
- Creates multiple sheets based on marketplace filters
- Sorts output to match input order

---

## 🛠️ Tech Stack
- Python 3
- Selenium (browser automation)
- Pandas (data processing)
- OpenPyXL (Excel manipulation)

---

## 📦 Requirements

Make sure you have:

- Python 3.8+
- Microsoft Edge installed
- Edge WebDriver (matching your browser version)

Install Python dependencies:

```bash
pip install -r requirements.txt
