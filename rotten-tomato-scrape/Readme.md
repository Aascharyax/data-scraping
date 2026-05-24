#  Rotten Tomatoes Movie Scraper

A simple Python web scraping project that collects movie titles from Rotten Tomatoes and exports the top 50 movies into an Excel sheet using Selenium and Pandas.

---

##  Features

- Scrapes movie titles from Rotten Tomatoes
- Uses Selenium for dynamic content loading
- Exports data to Excel (`.xlsx`)
- Beginner-friendly project
- Runs in Jupyter Notebook

---

## 🛠 Technologies Used

- Python
- Selenium
- Pandas
- OpenPyXL
- Jupyter Notebook

---

##  Installation

Install the required libraries:

```bash
pip install selenium pandas openpyxl
```

---

##  How to Run

1. Open Jupyter Notebook
2. Run the scraper script
3. The Excel file will be generated automatically

---

## 📁 Project Structure

```text
RottenTomatoesScraper/
│
├── scraper.ipynb
├── rotten_tomatoes_top50.xlsx
└── README.md
```

---

##  Output

The scraper generates:

```text
rotten_tomatoes_top50.xlsx
```

containing the scraped movie titles.

---

##  Notes

- Rotten Tomatoes uses dynamic loading, so Selenium is required.
- Website structure may change over time.
- Google Chrome and ChromeDriver must be installed.

---

##  Future Improvements

- Add movie ratings
- Add release year
- Export to CSV
- Scrape multiple pages
- Create a GUI or website version

---

##  Author

Created by Aascharya Paudel