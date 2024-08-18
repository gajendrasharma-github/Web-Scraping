# Guide to the repositories:

`1.` Scraping Ambition Box to gather company reviews, ratings, and other important information [Link](https://github.com/gajendrasharma-github/Web-Scraping/blob/main/Ambition%20Box%20Data%20Scraping.ipynb)

`2.` Scraping Ajio using Selenium with step by step process and guiding notes [Link](https://github.com/gajendrasharma-github/Web-Scraping/blob/main/Webscraping%20Selenium%20Ajio%20with%20Notes.ipynb)

`3.` Scraping Laptop Details from Amazon for a comprehensive analysis [Link](https://github.com/gajendrasharma-github/Web-Scraping/blob/main/Scraping%20Laptop%20Details%20from%20Amazon.ipynb)

`4.` Scraping Laptop Details from Amazon for the brand Asus [Link](https://github.com/gajendrasharma-github/Web-Scraping/blob/main/Extracting%20Laptop%20Details%20for%20Brand%20Asus%20Using%20Selenium.ipynb)

`5.` Scraping Election Outcomes from Election Commision of India Results Website [Link](https://github.com/gajendrasharma-github/India-2024-Election-Results-Streamlit-Visualization/blob/main/Election%20Results%20Scraping.ipynb)


## Introduction to Web Scraping

Web scraping is the automated process of extracting information from websites. It involves fetching the HTML content of a web page, parsing the data, and extracting the desired information for analysis or further processing. Web scraping is a powerful technique for gathering large amounts of data quickly and efficiently, often used for tasks such as price comparison, product reviews analysis, job listings aggregation, and more.


### Key Components of Web Scraping:

1. **HTML Parsing:** The process of breaking down the HTML structure of a webpage to access specific elements like text, images, and links.
2. **Data Extraction:** Identifying and extracting the relevant information from the parsed HTML, such as product prices, names, reviews, and more.
3. **Handling Dynamic Content:** Many websites use JavaScript to load content dynamically. Scraping such sites often requires simulating a real browser to capture all data.
4. **Data Storage:** Once the data is extracted, it is often stored in a structured format such as CSV, JSON, or a database for further analysis.

## Project Overview

This repository contains a series of scripts and notebooks developed from scratch to scrape data from various popular websites including Amazon, Ambition Box, Ajio, and others. Each script demonstrates a practical approach to web scraping, from simple static pages to more complex dynamic websites that require advanced techniques.

### Websites Scraped:

- **Amazon:** Extracting product details such as names, prices, ratings, and reviews.
- **Ambition Box:** Gathering company reviews, ratings, and employee feedback.
- **Ajio:** Scraping product listings, prices, discounts, and availability.

### Libraries and Tools Used:

- **BeautifulSoup:** For parsing HTML and navigating the page structure to extract specific elements.
- **Requests:** For sending HTTP requests to fetch the HTML content of web pages.
- **Selenium:** Used for handling dynamic content and interacting with JavaScript-rendered pages.
- **Pandas:** For storing and manipulating the scraped data in a tabular format.
