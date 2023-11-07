# Web_Scraping_BeautifulSoup
A basic Python script that utilizes BeautifulSoup, a library for parsing HTML and XML documents, along with requests, a library for making HTTP requests.

# Web Scraping with BeautifulSoup for Lengthy Text Hyperlinks

This Python script is designed to extract and display hyperlinks along with their text content from a specified website. The script filters and displays only those hyperlinks that have accompanying text content exceeding 35 characters.

## Overview

The provided Python script is a web scraping tool that uses the BeautifulSoup library for parsing HTML content and the Requests library for making HTTP requests. Its primary function is to gather and list hyperlinks from a given website, specifically targeting those links that have a significant amount of text associated with them.

## Usage

### Prerequisites

- Python 3.x
- Install required libraries using the following command:
    ```
    pip install beautifulsoup4 requests
    ```

### Execution

1. Open the Python script in your preferred editor.
2. Ensure that the `url` variable contains the desired website URL.
3. Run the script.
4. The output will display indexed hyperlinks with text content longer than 35 characters.

## Code Breakdown

- **Imports:** The script begins by importing the necessary libraries, BeautifulSoup and requests, to enable web scraping functionalities.
- **URL and Request:** It defines a specific URL for web scraping and uses the requests library to fetch the webpage content.
- **Parsing the Webpage:** BeautifulSoup is employed to parse the HTML content of the fetched webpage.
- **Finding Relevant Links:** The script iterates through anchor tags ('a') to identify and filter hyperlinks based on the length of their text content.
- **Print Output:** It prints a list of identified hyperlinks that meet the criteria (text content length greater than 35 characters).

## Notes

- This script is tailored to extract links with considerable text content, modifying the character limit criteria can be done by adjusting the `len(link.string) > 35` condition.

Feel free to use, modify, and integrate this code as needed.

For more details on the code and its functionality, check the script itself or feel free to reach out.

Happy scraping!
