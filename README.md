
# 🌐 Web Scraping Using Selenium in Python

This project demonstrates how to automate web browsing and extract data using **Selenium WebDriver** in Python.  
It was built as part of my coursework at Symbiosis and extended for hands-on understanding of DOM interaction, navigation, and dynamic scraping.

---

## 📌 Project Objective

The goal is to scrape content from [Wikipedia](https://en.wikipedia.org/) using different element targeting strategies (by ID, CLASS, TAG, LINK_TEXT, CSS). The script navigates between pages, extracts text, and prints meaningful data — useful in automating research, content collection, or structured extraction.

---

## 🚀 What This Script Does

- Launches a Chrome browser using Selenium
- Navigates to a target page (Wikipedia)
- Finds elements using:
  - ID
  - Class name
  - Tag name
  - Link text
  - CSS selector
- Clicks links, extracts paragraphs
- Collects and prints structured information

---

## 🧠 Tech Stack

| Tool             | Purpose                     |
|------------------|-----------------------------|
| Python           | Core scripting              |
| Selenium         | Browser automation          |
| webdriver-manager| Driver management (Chrome)  |

---

## 🗂️ File Structure

```
.
├── main.py                                            # Core scraping logic
├── requirements.txt                                   # Required libraries
├── .gitignore                                         # Python cache + logs
├── README.md                                          # You're reading it
└── Web Scraping Using Selenium in Python.ipynb        # Notebook version

```

---

## 🛠 How to Run

1. Install dependencies:
   
```bash
pip install -r requirements.txt
````

2. Run the script:

```bash
python main.py
```

✅ Ensure Google Chrome is installed and up to date.

---

## 📦 Output

Console output shows:

* Navigation events
* Extracted paragraph text
* Number of elements found per selector

---

## 🎓 Project Context

Built as part of a practical module on **Web Scraping Using Selenium** at BSE Institute.
Inspired by [naru94's GitHub repo](https://github.com/naru94/Web-Scraping-Using-Selenium-in-Python) and extended with additional features and documentation.

---

## 👤 Author

**\SAtya Sirisha Bolloju**
📊 Data Analyst | MSc Data Science – Symbiosis
🔗 [LinkedIn](https://www.linkedin.com/in/satya-sirisha-bolloju-031b33239/) 


