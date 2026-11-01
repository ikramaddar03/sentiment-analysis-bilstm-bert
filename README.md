# Sentiment Analysis using BiLSTM and BERT

## Project Overview

This project focuses on sentiment analysis using Natural Language Processing (NLP) and Deep Learning.

It explores two different approaches:

### 1. BiLSTM Model (TensorFlow / Keras)

- Uses the IMDb movie reviews dataset.
- Preprocesses text data using sequence padding.
- Implements a Bidirectional LSTM neural network.
- Classifies reviews into Positive and Negative sentiments.
- Evaluates performance using accuracy and loss curves.

### 2. Multilingual BERT Model (Hugging Face)

- Uses the pre-trained model `nlptown/bert-base-multilingual-uncased-sentiment`.
- Analyzes reviews in English, French, and Arabic.
- Predicts sentiment using a 1-to-5-star rating system.
- Maps predictions into Positive, Neutral, and Negative categories.

## Technologies Used

- Python
- Jupyter Notebook
- TensorFlow / Keras
- PyTorch
- Hugging Face Transformers
- NumPy
- Matplotlib

## Dataset

The BiLSTM model is trained and evaluated using the IMDb movie reviews dataset provided by TensorFlow/Keras.

## Installation

```bash
pip install -r requirements.txt
```

## How to Run

1. Clone this repository.
2. Install the dependencies.
3. Launch Jupyter Notebook using `jupyter notebook`.
4. Open `sentiment_analysis_bilstm_bert.ipynb`.
5. Run the notebook cells.

## Author

**Ikram Addar**

GitHub: [ikramaddar03](https://github.com/ikramaddar03)
