# FastText Analysis on Yelp Dataset

## Description

This script processes text data from the Yelp dataset, trains a FastText model on the processed text, and compares the trained model's word similarities with those from a pre-trained FastText model. The script utilizes `nltk` for text preprocessing and `gensim` for training and analyzing the FastText model.

## Installation

To use this script, you need to have Python installed on your system. Additionally, you need to install the required libraries. Follow the steps below to set up your environment:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/fasttext-analysis.git
    cd fasttext-analysis
    ```

2. Install the required Python packages:

    ```bash
    pip install numpy pandas nltk gensim tabulate
    ```

3. Download necessary NLTK data:

    ```python
    import nltk
    nltk.download('wordnet')
    nltk.download('omw-1.4')
    ```

4. Ensure you have access to the Yelp dataset JSON file and place it in the appropriate directory or modify the path in the script.

## Usage

To run the script, simply execute it with Python:

```bash
python fasttext_analysis.py
```

The script performs the following tasks:

1. Loads and preprocesses text data from the Yelp dataset.
2. Trains a custom FastText model on the processed text.
3. Loads a pre-trained FastText model for comparison.
4. Analyzes and compares word similarities between the custom model and the pre-trained model.
5. Outputs tables of top 10 similar and opposite words for selected words in both models.

## Features

- **Text Preprocessing**: Cleans and normalizes text from the Yelp dataset.
- **Custom FastText Model Training**: Trains a FastText model with specified parameters.
- **Pre-trained Model Comparison**: Compares word similarities between the custom model and a pre-trained FastText model.
- **Analysis Output**: Provides tables of similar and opposite words for selected words.



