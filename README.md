# 📘 Books Web Scraper

A Python project to scrape book information from [Books to Scrape](http://books.toscrape.com/), a website designed for practicing web scraping. This project extracts book titles, prices, availability, and star ratings using **BeautifulSoup**, and applies **machine learning models** for classification and regression tasks on the scraped data.

---

## 🔍 Features

- 📚 Scrapes book details from multiple pages
- 💰 Extracts price, availability, and star rating
- 📊 Applies classification to predict star rating categories
- 📈 Uses regression to analyze or predict book prices
- 📦 Saves data to CSV for further analysis
- 💡 Easy-to-read and beginner-friendly code

---

## 🛠️ Tech Stack

- Python
- BeautifulSoup – HTML parsing
- Requests – fetching web content
- Pandas – data manipulation
- Scikit-learn – classification and regression models
- Jupyter Notebook

---
## 🧠 ML Tasks Performed

### ✅ Classification
- **Goal**: Predict book rating category (e.g., ★★★☆☆, ★★★★☆) using features like price, availability, and title length.
- **Model Used**: Random Forest / Logistic Regression (customizable)

### ✅ Regression
- **Goal**: Predict the price of a book based on its features (e.g., rating, title features, availability)
- **Model Used**: Linear Regression / Decision Tree Regressor

---
## 📈 Example ML Insights

- 💬 “Books with higher star ratings tend to be priced slightly higher on average.”
- 📊 “Out-of-stock books have lower average ratings.”

---
