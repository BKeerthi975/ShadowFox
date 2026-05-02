# 🐍 ShadowFox Python Development Internship

This repository contains all tasks completed during my **Python Development Internship at ShadowFox**.  
The tasks cover core Python programming concepts, data structures, OOP, and real-world mini-projects — all built using Jupyter Notebooks.

---

## 🗂️ Repository Structure

```
📦 ShadowFox
 ┣ 📁 Task 1   → Python Fundamentals
 ┣ 📁 Task 2   → Data Structures & OOP
 ┣ 📁 Task 3   → Mini Projects & Data Analysis
 ┗ 📜 README.md
```

---

## ✅ Task 1 — Python Fundamentals

### 📌 Numbers & Math Operations (`numbers.ipynb`)
- Used Python's `format()` function to convert a number to octal representation
- Calculated the area of a circular pond using the formula **π × r²**, then computed total water volume in liters
- Calculated speed (meters/second) from distance and time, printing the result without decimals using `int()`

### 📌 Conditional Logic — If/Else (`if_condition.ipynb`)
Three programs using `if/elif/else` conditions:
- **BMI Calculator** — Takes height and weight as input, calculates BMI, and classifies into: `Underweight`, `Normal`, `Overweight`, or `Obesity`
- **City-to-Country Mapper** — Identifies which country (India, UAE, Australia) a given city belongs to using list lookups
- **Same Country Checker** — Takes two city names and checks whether both belong to the same country, using a helper `find_country()` function

### 📌 First Program (`firstpro.ipynb`)
- Classic `Hello World` — the very first Python program

---

## ✅ Task 2 — Data Structures & OOP

### 📌 Lists — Justice League Manager (`List.ipynb`)
A list-based superhero management program:
- Counted total members using `len()`
- Added new members (Batgirl, Nightwing) with `append()`
- Made Wonder Woman the leader by repositioning her to index 0 using `remove()` + `insert()`
- Separated conflicting heroes (Aquaman & Flash) by inserting Superman between them
- Replaced the entire team with a new set of heroes
- Sorted the team alphabetically — the hero at index 0 automatically becomes the new leader

### 📌 Dictionaries — Trip Expense Tracker (`dictionary.ipynb`)
Two tasks using Python dictionaries:
- **Name-Length Tuples**: Created a list of friends' names and built a list of `(name, len(name))` tuples using list comprehension
- **Travel Expense Comparison**: Two dictionaries tracking expenses across 5 categories (Hotel, Food, Transportation, Attractions, Miscellaneous). Compared total spending and identified the category with the biggest spending difference using a loop

### 📌 OOP — Inheritance (`Inheritence.ipynb`)
Five-part OOP exercise using `MobilePhone` as the base class:
1. Created `Apple` and `Samsung` as child classes inheriting from `MobilePhone` — printed phone specs via an inherited method
2. Added mobile phone functionalities: `make_call()`, `receive_call()`, `take_a_picture()` — demonstrated full polymorphic behavior
3. Used `super()` to call the parent class constructor from child classes, passing brand-specific values
4. Created multiple `Apple` objects with different model specs (iPhone SE, iPhone 13, iPhone 14 Pro, iPhone X)
5. Created multiple `Samsung` objects with different model specs (Galaxy M13, Galaxy S21, Galaxy A32, Galaxy Z Flip)

---

## ✅ Task 3 — Mini Projects & Data Analysis

### 🎮 Hangman Game (`Hangman.ipynb`)
A fully functional word-guessing game:
- Random word selected from a list of 5 words, each paired with a hint
- Visual progress display showing guessed letters and blanks
- 6 attempts allowed — wrong guess decrements the attempt counter
- Handles duplicate guesses gracefully ("You already guessed that letter")
- Play again option after each round

### 🌐 Web Scraper (`webscraper.ipynb`)
A live web scraper using **BeautifulSoup** and **Requests**:
- Target site: [books.toscrape.com](http://books.toscrape.com)
- Extracts all 20 book titles and prices from the homepage
- Parses HTML with `html.parser`
- Includes `try/except` error handling for HTTP request failures

### 📊 Online Retail Sales Analysis (`sales_analysis.ipynb`)
Exploratory data analysis on a real-world UK retail dataset (`online_retail.csv`) using **Pandas**, **Matplotlib**, and **Seaborn**:
- Loaded and cleaned data: removed rows with missing `CustomerID`, filtered out returns (negative quantities) and zero-price items
- Engineered a new `TotalPrice` column: `Quantity × UnitPrice`
- Converted `InvoiceDate` to datetime and set it as the index for time-series analysis
- **Top 10 Countries by Total Sales** — horizontal bar chart showing the highest revenue-generating countries
- **Monthly Sales Trend** — line chart showing how total sales fluctuated month by month over the dataset's time range
- **Top 10 Most Popular Products** — horizontal bar chart showing the highest quantity-sold products

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core programming language |
| Jupyter Notebook | Development environment |
| BeautifulSoup4 | Web scraping |
| Requests | HTTP requests |
| Pandas | Data loading, cleaning, and analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical chart styling |

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/BKeerthi975/ShadowFox.git
cd ShadowFox
```

2. Install dependencies:
```bash
pip install beautifulsoup4 requests pandas matplotlib seaborn openpyxl
```

3. Open any notebook in Jupyter:
```bash
jupyter notebook
```

---

## 👩‍💻 About

**Intern:** B. Keerthi  
**Internship:** Python Development Intern — ShadowFox  
**Tools:** Python, Jupyter Notebook, Pandas, Matplotlib, Seaborn, BeautifulSoup  
**GitHub:** [BKeerthi975](https://github.com/BKeerthi975)
