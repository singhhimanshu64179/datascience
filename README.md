# 🧠 Quote Guessing Game (Web Scraper)

A fun command-line game built with **Python**, where you try to guess who said a randomly selected quote.  
The program scrapes real quotes and authors from [quotes.toscrape.com](http://quotes.toscrape.com) using **BeautifulSoup** and **Requests**.

---

## 🚀 Features

- Scrapes all quotes from multiple pages on [quotes.toscrape.com](http://quotes.toscrape.com)
- Randomly selects a quote for the user to guess
- Provides up to **4 guesses** with helpful hints:
  1. Author’s birth date and place  
  2. First letter of the author’s first name  
  3. First letter of the author’s last name  
- Uses polite scraping with a delay between requests (`sleep(2)`)

---

## 🧩 Technologies Used

- **Python 3.x**
- **Requests** — for making HTTP requests  
- **BeautifulSoup (bs4)** — for HTML parsing and data extraction  
- **Time & Random modules** — for gameplay timing and randomness  

---
