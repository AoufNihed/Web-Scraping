# Web Scraping Project

This project demonstrates how to scrape data from a webpage using Python's BeautifulSoup library and save the extracted data into a CSV file using Pandas. The code is written and executed in a Jupyter Notebook.

## Table of Contents

- [Project Description](#project-description)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)


## Project Description

The goal of this project is to scrape data from websites and process it using Python. The primary tools used for web scraping are BeautifulSoup and requests. The extracted data is then organized and saved into a CSV file using Pandas.

### Steps to Scrape Data and Save to CSV

1. **Import necessary libraries**: Import BeautifulSoup for parsing HTML, requests for sending HTTP requests, and pandas for data manipulation and storage.
2. **Send a request to the website and parse HTML**: Use requests to get the HTML content of the webpage and BeautifulSoup to parse the HTML.
3. **Extract data from the HTML**: Locate the specific elements containing the data you need using BeautifulSoup's methods such as `find` and `find_all`.
4. **Organize data into a DataFrame**: Create a Pandas DataFrame to store the extracted data.
5. **Save the DataFrame to a CSV file**: Use the `to_csv` method of the DataFrame to save the data into a CSV file.

Example websites scraped in this project include:
- [Scrape This Site](https://www.scrapethissite.com/pages/forms/)
- [Wikipedia - List of largest companies in the United States by revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/aoufnihed/web-scraping-project.git
    cd web-scraping-project
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

## Usage

Open the Jupyter Notebook containing the code and run the cells to perform web scraping and save the data to a CSV file. The notebook includes detailed comments and explanations for each step of the process.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


