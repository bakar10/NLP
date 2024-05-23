# Wikipedia Text Processing and Text Generation

## Description

This script fetches content from Wikipedia, preprocesses it for text analysis, and explores text generation using SimpleRNN models. It demonstrates character-based and word-based text generation techniques.

## Installation

To use this script, you need to have Python installed on your system. Additionally, install the required libraries by executing the following command:

```bash
pip install wikipedia nltk gensim tensorflow
```

## Usage

Run the script using Python:

```bash
python wikipedia_text_processing.py
```

The script performs the following tasks:

1. Fetches content from Wikipedia on a given topic.
2. Preprocesses the text data by tokenizing, removing stopwords, stemming, and lemmatizing.
3. Generates embedding vectors for the preprocessed text using a pre-trained FastText model.
4. Prepares data for both character-based and word-based text generation.
5. Trains SimpleRNN models for both character-based and word-based text generation.
6. Generates text using both models.

## Features

- **Wikipedia Content Fetching**: Fetches content from Wikipedia, handling ambiguous topics.
- **Text Preprocessing**: Tokenization, stopword removal, stemming, lemmatization, and character-level cleaning.
- **Embedding Generation**: Utilizes a pre-trained FastText model to generate embedding vectors for text.
- **Text Generation**: Demonstrates both character-based and word-based text generation using SimpleRNN models.
- **Evaluation**: Prints training loss and accuracy for the trained models.

## Dependencies

- `wikipedia`: For fetching content from Wikipedia.
- `nltk`: For text preprocessing.
- `gensim`: For loading pre-trained FastText model.
- `tensorflow`: For building and training SimpleRNN models.

## Example Output

Generated Character-based Text :
Ared Bald B
Generated Word-based Text with Direct Sampling:
lionel guardiola argentine nine since messi youth game contemporary 2007 time
