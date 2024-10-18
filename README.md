# Book Scraper and Recommendation System

This project is a web scraper for books from the website [Books to Scrape](https://books.toscrape.com), and it also includes data analysis and a recommendation system based on categories and ratings. The scraper gathers data on book titles, prices, ratings, categories, and descriptions, storing them in a CSV file. Additionally, it allows for data analysis and integrates OpenAI's API to recommend books based on user preferences.

## Features

1. **Web Scraping:**
   - Scrapes book data (title, price, star rating, category, and description) from multiple pages of the Books to Scrape website.
   - Saves the scraped data into a CSV file (`books_data.csv`).

2. **Data Analysis:**
   - Analyzes the scraped data to determine:
     - Number of books per category.
     - Average price per category.
     - Average star rating per category.
   - Visualizes the number of books per category using a bar chart.

3. **Book Recommendation:**
   - Recommends books based on category and minimum star rating.
   - Integrates OpenAI's API to provide AI-based recommendations.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/book-scraper.git
   cd book-scraper
