# 📚 Web Scraping of Oxfordbook Store (New Releases Books)

## 🚀 Project Overview

This project involves web scraping the Oxfordbook Store website to extract information about new book releases. The script is developed using Python, leveraging the BeautifulSoup library for parsing HTML and extracting the required data. The collected data is cleaned, preprocessed, and ready for further analysis or visualization.

## 🛠️ Features

- **Scraping**: Automated extraction of book details such as title, author, price, and publication date.
- **Data Cleaning**: Processing and cleaning the scraped data to ensure accuracy and consistency.
- **Data Export**: Exporting the cleaned data to a CSV file for easy access and analysis.
- **Error Handling**: Robust error handling to manage exceptions during the scraping process.

## 📂 Project Structure

```bash
.
├── notebooks
│   └── Oxfordbook_Scraping.ipynb  # Jupyter notebook with the scraping script
├── data
│   └── oxfordbooks_new_releases.csv  # CSV file with scraped data
├── scripts
│   └── scraper.py  # Python script for web scraping
├── README.md  # Project documentation
└── requirements.txt  # Dependencies
