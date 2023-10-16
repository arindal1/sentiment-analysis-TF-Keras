
# Sentiment Analysis with TensorFlow and Keras

This project demonstrates sentiment analysis using a neural network built with TensorFlow and Keras. The model is trained to classify text into three sentiment categories: negative, neutral, and positive.

## Introduction

Sentiment analysis, also known as opinion mining, involves analyzing and understanding the sentiment expressed in a piece of text. This project employs a neural network to predict the sentiment of input text.

## Installation

To set up and run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

- **Preprocessing**: The text data is preprocessed and tokenized using TensorFlow's Tokenizer. The sequences are padded to a fixed length for consistency.

- **Model**: A neural network model is defined using Keras, with an Embedding layer, GlobalAveragePooling1D, and Dense layers. The model is compiled and trained on the provided dataset.

- **Evaluation**: The model is evaluated on a test dataset to measure its performance.

- **Interactive Prediction**: Users can interactively input a sentence for sentiment analysis, and the trained model predicts the sentiment of the input.

## Model Training

- If the saved model exists, it is loaded.
- If not, a new model is trained using the provided dataset and saved for future use.

## Interactive Prediction

To predict sentiment for a custom input, run the provided script and follow the prompts.

```bash
python interactive_predict.py
```
