# Course Scraper for McGill University

This project is a Version 1 web scraper developed using **Beautiful Soup** to collect comprehensive information about the degrees and courses offered at **McGill University**.

## 📌 Features

- **soup_maker**: Quickly creates BeautifulSoup objects for parsing HTML.
- **url_page_collector**: Gathers all relevant URLs of degree pages from McGill's website.
- **extract_courses**: Extracts detailed course data like code, name, credits, description, instructors, and prerequisites.
- **extract_all**: Combines and organizes extracted course information into a structured dictionary.

## 🧪 Example

The scraper has been tested on various McGill program URLs and successfully extracts structured course data, ready for further analysis or presentation.

## 🔧 Technologies Used

- Python
- BeautifulSoup
- Requests

## 🚀 Future Work

- Add pagination support
- Export data to CSV or JSON
- Improve error handling and scraping speed
