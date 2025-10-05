# 🛒 Amazon Product Data Scraper (Selenium + Python)

## 📖 Overview
This project is a **Python-based web scraper** that automatically collects product details from Amazon using **Selenium WebDriver**.  
It extracts key information such as **Product Title**, **Price**, and **Rating**, then exports the data into a clean **Excel file (`amazon.xlsx`)**.

The scraper is built to handle missing or dynamic elements gracefully, ensuring smooth performance even when some products lack prices or ratings.

---

## ⚙️ Features
- 🏷️ Extracts product **titles**, **prices**, and **ratings**  
- ✅ Handles missing elements without breaking  
- ⏱️ Works with dynamically loaded content  
- 📊 Exports results to **Excel (.xlsx)**  
- 🔁 Can easily be extended to handle multiple pages  

---

## 🧰 Tech Stack
- **Python 3**
- **Selenium WebDriver**
- **Pandas**
- **OpenPyXL**
- **ChromeDriver** (via `webdriver-manager`)

---

## 🚀 How It Works
1. Opens Amazon using Selenium and ChromeDriver.  
2. Locates each product container using CSS selectors.  
3. Extracts text data for the product title, price, and rating.  
4. Handles missing elements safely (assigns “No price” or “No rating”).  
5. Saves the final structured data into `amazon.xlsx`.

---

## 🧑‍💻 Installation & Setup

### 1️⃣ Clone this repository
```bash
git clone https://github.com/tajamulnur/amazon-webscraper.git
cd amazon-webscraper

