# Web Text Scraper

## Description

Web Text Scraper is a Python script that extracts text from a specified webpage, processes it by cleaning, tokenizing, lemmatizing, and removing stop words, and finally outputs a set of unique words. This script uses various libraries including `requests`, `BeautifulSoup`, and `nltk` for web scraping and natural language processing.

## Installation

To use this script, you need to have Python installed on your system. You also need to install the required libraries. Follow the steps below to set up your environment:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/web-text-scraper.git
    cd web-text-scraper
    ```

2. Install the required Python packages:

    ```bash
    pip install nltk requests beautifulsoup4
    ```

3. Download necessary NLTK data:

    ```python
    import nltk
    nltk.download('stopwords')
    nltk.download('wordnet')
    nltk.download('punkt')
    ```

## Usage

To run the script, simply execute it with Python:

```bash
python web_text_scraper.py
```

The script sends a GET request to the specified URL, extracts text from the paragraphs, processes the text, and prints unique words found on the page.

## Features

- **Web Scraping**: Extracts text from a specified webpage.
- **Text Cleaning**: Removes unwanted symbols or characters and converts text to lowercase.
- **Tokenization**: Splits text into words.
- **Lemmatization**: Converts words to their base form.
- **Stop Words Removal**: Removes common English stop words.
- **Unique Words Extraction**: Outputs a set of unique words found on the webpage.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

