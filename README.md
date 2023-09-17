# Text-Analysis-Project
# Text Analysis and Web Scraping Project

This project combines web scraping and text analysis to extract and analyze text data from a list of URLs provided in an Excel file.

## Overview

- The project consists of two main parts:
  1. Web Scraping: It extracts article text content from a list of URLs.
  2. Text Analysis: It performs various text analysis tasks on the extracted text, including sentiment analysis, readability analysis, and more.

## Prerequisites

Before running the project, make sure you have the following installed:

- Python 3.x
- Required Python libraries (you can install them using `pip`):
  - requests
  - beautifulsoup4
  - openpyxl
  - nltk
  - textblob
  - syllables

You can install the required Python libraries using the following command:

```bash
pip install requests beautifulsoup4 openpyxl nltk textblob syllables


Usage
Web Scraping

Create an input Excel file (Input.xlsx) with a list of URLs in the second column (Column B). The first column (Column A) can be used for unique URL IDs.

Run the web_scraping.py script to extract article text content from the provided URLs. The extracted text will be saved in separate text files named after the URL IDs.

Text Analysis

After web scraping, you can perform text analysis on the extracted text.

Create or update the following files as needed:

positive_words.txt: A list of positive words (one word per line).
negative_words.txt: A list of negative words (one word per line).
combined_file.txt: A list of additional stop words (one word per line).
Run the text_analysis.py script to analyze the extracted text. The analysis results will be saved in an output Excel file (Output.xlsx).

File Structure
web_scraping.py: Python script for web scraping and saving article text to text files.
text_analysis.py: Python script for analyzing the extracted text and saving results to an Excel file.
positive_words.txt: List of positive words.
negative_words.txt: List of negative words.
combined_file.txt: Additional stop words.
Input.xlsx: Excel file containing URLs for web scraping.
Output.xlsx: Excel file containing text analysis results.
Contributing
Contributions are welcome! If you have suggestions or improvements, please create a new issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
