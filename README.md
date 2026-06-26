# 📚 Web Scraping to Data Analytics: Book Store Analysis using Python, PostgreSQL & Power BI

## 📖 Project Overview

This project demonstrates a complete **end-to-end data analytics workflow**, beginning with **web scraping** and ending with business insights and data visualization.

Instead of using an existing dataset, the data was first collected by scraping an online bookstore using Python. The scraped data was stored as a CSV file, cleaned and transformed using Pandas, imported into PostgreSQL for SQL analysis, and finally explored through visualizations to generate meaningful business insights.

This project showcases the complete lifecycle of a data analytics project, including data collection, preprocessing, database management, SQL analysis, exploratory data analysis (EDA), and dashboard preparation.

---

# 🚀 Project Workflow

```
Website
      │
      ▼
Web Scraping (Python + BeautifulSoup)
      │
      ▼
Raw CSV Dataset
      │
      ▼
Data Cleaning & Preprocessing (Pandas)
      │
      ▼
Cleaned CSV Dataset
      │
      ▼
PostgreSQL Database
      │
      ▼
SQL Analysis
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Data Visualization
      │
      ▼
Business Insights
      │
      ▼
Power BI Dashboard
```

---

# 🎯 Objectives

* Scrape book information from an online bookstore.
* Store the scraped data as a CSV dataset.
* Clean and preprocess the dataset using Pandas.
* Import the cleaned dataset into PostgreSQL.
* Perform SQL queries to answer business questions.
* Conduct Exploratory Data Analysis (EDA).
* Create visualizations to identify trends and patterns.
* Build an interactive Power BI dashboard.
* Generate business insights and recommendations.

---

# 🛠️ Technologies Used

### Programming

* Python

### Web Scraping

* Requests
* BeautifulSoup

### Data Processing

* Pandas

### Database

* PostgreSQL
* SQL

### Visualization

* Matplotlib

### Dashboard

* Power BI

### Development Tools

* Jupyter Notebook
* pgAdmin 4
* VS Code

# 📊 Dataset

The dataset was **not downloaded from any public source**. It was created by scraping an online bookstore using Python - 
web : "https://books.toscrape.com/catalogue/page-{}.html".

### Dataset Features

| Column       | Description             |
| ------------ | ----------------------- |
| Title        | Book title              |
| Price        | Book price              |
| Rating       | Book rating (1–5 Stars) |
| Availability | Stock availability      |

**Total Records:** 1,000 Books

---

# 🔍 Project Steps

## 1. Web Scraping

* Connected to the bookstore website.
* Scraped book details using Requests and BeautifulSoup.
* Collected:

  * Book Title
  * Price
  * Rating
  * Availability
* Saved the scraped data as **raw_books.csv**.

---

## 2. Data Cleaning

The raw dataset was cleaned by:

* Removing unwanted currency symbols.
* Converting prices into numeric values.
* Checking missing values.
* Removing duplicate records.
* Standardizing column formats.
* Saving the cleaned dataset as **cleaned_books.csv**.

---

## 3. PostgreSQL Database

* Created a PostgreSQL database.
* Designed the `books` table.
* Imported the cleaned CSV dataset.
* Verified data integrity.

---

## 4. SQL Analysis

Performed SQL queries to answer business questions such as:

* Total number of books
* Average book price
* Highest and lowest priced books
* Rating distribution
* Average price by rating
* Premium vs Budget books
* Top expensive books
* Books above average price

---

## 5. Exploratory Data Analysis (EDA)

Generated visualizations including:

* Price Distribution
* Rating Distribution
* Average Price by Rating
* Top 10 Expensive Books
* Top 10 Cheapest Books
* Price Boxplot
* Availability Distribution
* Rating vs Price Scatter Plot

---

## 6. Business Insights

Key findings include:

* Successfully collected data for 1,000 books through web scraping.
* Most books fall within a moderate price range.
* Higher-rated books are not necessarily more expensive.
* Premium-priced books represent a smaller portion of the catalog.
* The dataset provides useful information for pricing and inventory analysis.

---

# 📸 Project Screenshots

Include screenshots of:

* Web Scraping Output
* Raw CSV Dataset
* Cleaned Dataset
* PostgreSQL Table
* SQL Query Results
* EDA Charts
* Power BI Dashboard

---

# 🚀 Future Improvements

* Scrape additional attributes such as book category, UPC, product description, and image URL.
* Automate the ETL pipeline.
* Schedule periodic data collection.
* Deploy an interactive dashboard.
* Expand the analysis with advanced SQL and machine learning models.

---

# ⭐ Skills Demonstrated

* Web Scraping
* Data Collection
* Data Cleaning
* Data Preprocessing
* SQL
* PostgreSQL
* Exploratory Data Analysis
* Data Visualization
* Business Analytics
* Power BI
* Git & GitHub

---

# 👨‍💻 Author

**Ritik Saini**

If you found this project useful, consider giving it a ⭐ on GitHub.
