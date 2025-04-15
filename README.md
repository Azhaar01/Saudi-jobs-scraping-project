# Saudi-jobs-scraping-project

This project scrapes job listings from Wuzzuf for positions in Saudi Arabia. It includes data extraction and cleaning to prepare the dataset for further analysis or use.

## 📚 Data Source

- [Wuzzuf - Saudi Arabia Job Listings](https://wuzzuf.net/saudi/search/jobs/?filters%5Bcountry%5D%5B0%5D=Saudi%20Arabia)

## 📌 Features

- Scrapes job title, company name, location, job type, job location type, experience level, experience years, job category, and required skills.
- Cleans object columns by:
  - Removing unwanted symbols like `·`, `-`, or special characters.
  - Replacing middle dots with dashes.
  - Standardizing text format.
  - Checked for null values and handled duplicates.

## 🧪 Technologies Used

- Python
- BeautifulSoup
- Pandas

## 📂 Files Included

- `Web_Scraping_Jobs_Project.ipynb` – the web scraping and cleaning script.
- `Dataset_Cleaned.csv` – the cleaned dataset.
