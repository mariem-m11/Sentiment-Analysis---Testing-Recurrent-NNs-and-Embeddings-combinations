# Sentiment Analysis on IMDB Movie Reviews

## Objective
The main objective of this project was to determine the most effective combination of RNN architecture and word embeddings for classifying sentiments expressed in movie reviews as either positive or negative.

## Dataset
The dataset used is the IMDB dataset, which contains movie reviews labeled for sentiment (positive/negative).

## Models and Technologies
- **Recurrent Neural Networks (RNNs)**: LSTM, GRU, CRNN
- **Embeddings**: GloVe, Word2Vec, FastText
- **Framework**: TensorFlow

### Prerequisites
- Python 3.8 or above
- TensorFlow 2.x
- enwiki_20180420_100d.txt (Word2vec)
- glove.6B.100d.txt (Glove)
- cc.en.300.bin (Fasttext)

## Results
The combination of GRU and FastText embedding achieved the best performance with an accuracy of 0.87.
