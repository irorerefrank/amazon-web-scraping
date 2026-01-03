# Amazon Web Scraping Project (Python)

## Project Overview
This project demonstrates how to use Python to scrape product information from Amazon product pages. The goal was to practice real-world web scraping techniques, including sending HTTP requests, handling headers, parsing HTML, and extracting structured data from a dynamic website.

The script focuses on collecting basic product details such as:
- Product title  
- Product price  
- Date the data was collected  

---

## Tools & Libraries Used
- Python  
- Requests – for sending HTTP requests  
- BeautifulSoup – for parsing and extracting data from HTML  
- Datetime – for tracking when the data was scraped  

---

## How the Project Works
1. A request is sent to an Amazon product page using realistic browser headers.
2. The HTML response is parsed using BeautifulSoup.
3. Specific HTML elements are targeted to extract the product title and price.
4. The extracted data is cleaned and displayed in a readable format.
5. The project is designed as a learning exercise to understand how large e-commerce sites structure their pages.

---

## Key Learnings
- Inspecting and navigating complex HTML structures  
- The importance of request headers when scraping real websites  
- Handling missing or changing HTML elements  
- Understanding challenges caused by anti-bot protections  
- Writing defensive code to avoid errors when data is unavailable  

---

## Limitations
Amazon actively implements anti-scraping measures, and its page structure can change frequently. As a result:
- The script may stop returning results if requests are blocked
- HTML selectors may need updates over time
- This project is intended for educational purposes only  

These limitations reflect real-world challenges commonly faced in web scraping projects.

---

## Future Improvements
- Add proxy or user-agent rotation
- Store scraped data in CSV or database format
- Improve error handling and logging
- Adapt the scraper to handle multiple product pages

---

## Disclaimer
This project was created strictly for learning and portfolio demonstration purposes. It is not intended for commercial use or large-scale scraping.
