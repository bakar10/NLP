# CNN Text Classification on Sentiment Analysis Dataset

## Description

This script performs sentiment analysis on a text dataset using multiple Convolutional Neural Network (CNN) architectures. It includes data preprocessing, model training, and evaluation of three different CNN models with varying complexities.

## Installation

To use this script, you need to have Python installed on your system. Additionally, you need to install the required libraries. Follow the steps below to set up your environment:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/cnn-text-classification.git
    cd cnn-text-classification
    ```

2. Install the required Python packages:

    ```bash
    pip install pandas dask scikit-learn tensorflow
    ```

3. Download necessary NLTK data:

    ```python
    import nltk
    nltk.download('wordnet')
    nltk.download('omw-1.4')
    ```

## Usage

To run the script, simply execute it with Python:

```bash
python cnn_text_classification.py
```

The script performs the following tasks:

1. Loads the sentiment dataset.
2. Tries different encodings to read the dataset.
3. Preprocesses the text data.
4. Trains three CNN models with different complexities.
5. Evaluates and prints the performance of each model on the test set.

## Dataset

Ensure you have access to the sentiment dataset `training.1600000.processed.noemoticon.csv` and place it in the appropriate directory or modify the path in the script.

## Features

- **Data Loading with Encoding Handling**: Tries multiple encodings to successfully read the dataset.
- **Text Preprocessing**: Tokenizes and pads text data for model training.
- **Model Training**: Trains three CNN models with different architectures.
- **Model Evaluation**: Evaluates the models on the test set and prints the results.

## Model Architectures

1. **Basic CNN Model**:
    - Embedding layer
    - Conv1D layer
    - GlobalMaxPooling1D layer
    - Dense layer with dropout

2. **Simplified CNN Model**:
    - Embedding layer
    - Conv1D layer
    - GlobalMaxPooling1D layer
    - Dense layer

3. **Complex CNN Model**:
    - Embedding layer
    - Multiple Conv1D and MaxPooling1D layers
    - GlobalMaxPooling1D layer
    - Dense layer

## Example Output

The script will print the evaluation results for each model, such as:

```
Test Loss: 0.4204
Test Accuracy: 0.8445

Test Loss (Simple Model): 0.4122
Test Accuracy (Simple Model): 0.8464

Test Loss (Complex Model): 0.4418
Test Accuracy (Complex Model): 0.8141
```

