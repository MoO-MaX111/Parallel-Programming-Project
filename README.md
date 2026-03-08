# Book Scraper (Parallel Programming & Multithreading)

## Project Description
This project is a **Book Scraper** that automatically collects book data from a website.  
The program extracts information such as **book title, price, rating, and link** and stores it in a structured file.

The project uses **Parallel Programming and Multithreading** to speed up the scraping process instead of loading pages sequentially.

---

## Features
- Scrape book data from a website
- Extract information such as:
  - Book Title
  - Price
  - Rating
  - Product Link
- Store the collected data in a **CSV or JSON file**
- Use **Multithreading** to improve performance
- Implement **Parallel processing** to handle multiple pages at the same time

---

## Technologies Used
- Python
- Requests
- BeautifulSoup
- Threading / Concurrent Futures

---

## How It Works
1. The program sends requests to the website to get book pages.
2. The pages are divided among multiple **threads**.
3. Each thread processes a page and extracts the required data.
4. All extracted data is collected into a single list.
5. The final data is saved into a structured file.

---

## Example Output

| Book Title | Price | Rating |
|------------|-------|--------|
| Book A     | £20   | ⭐⭐⭐⭐ |
| Book B     | £15   | ⭐⭐⭐  |

---

## Project Goal
The goal of this project is to:
- Learn **Web Scraping**
- Understand **Parallel Programming**
- Improve program performance using **Multithreading**
