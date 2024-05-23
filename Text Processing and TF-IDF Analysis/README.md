# Text Generation and TF-IDF Analysis

## Description

This script generates text based on specified topics using a text generation model (GPT-2), preprocesses the text by cleaning, normalizing, and removing stop words, and computes TF-IDF values for the words in the generated documents. It provides both a manual implementation of TF-IDF and a scikit-learn based implementation.

## Installation

To use this script, you need to have Python installed on your system. Additionally, you need to install the required libraries. Follow the steps below to set up your environment:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/text-generation-tfidf.git
    cd text-generation-tfidf
    ```

2. Install the required Python packages:

    ```bash
    pip install nltk transformers scikit-learn
    ```

3. Download necessary NLTK data:

    ```python
    import nltk
    nltk.download('punkt')
    nltk.download('stopwords')
    ```

## Usage

To run the script, execute the following command:

```bash
python text_generation_tfidf.py
```

The script generates text based on specified topics, preprocesses the text, and computes TF-IDF values for the words in the generated documents.

## Features

- **Text Generation**: Generates text based on given topics using the GPT-2 model.
- **Text Preprocessing**: Cleans, normalizes, and preprocesses the generated text.
- **TF-IDF Calculation**: Computes TF-IDF values manually and using scikit-learn's `TfidfVectorizer`.



## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

