## **Project Title : Sentiment Analysis on IMDb Movie Reviews**



## Problem Statement

The goal of this project is to build deep learning models to predict the sentiment (positive or negative) of movie reviews from the IMDb dataset. By analyzing the text of the reviews, we aim to classify them as either positive or negative based on the words and patterns in the text.

---


## Dataset Link

The dataset used is the **IMDb Movie Reviews Dataset**, containing 50,000 labeled reviews.

- **Kaggle IMDb Dataset**: (https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

---

## Explanation

This project explores three deep learning techniques to perform sentiment analysis:

1. **Convolutional Neural Networks (CNN)**: CNNs are well-known for their effectiveness in detecting local patterns and features. In this task, they can capture important features from the text sequences and classify the sentiment.
2. **Recurrent Neural Networks (RNN)**: RNNs are used for sequential data, such as text, as they maintain a memory of previous words in a sequence. We use RNNs to capture the temporal dependencies in reviews.
3. **Gated Recurrent Units (GRU)**:  GRUs, a variant of RNNs, offer a more efficient way to learn long-term dependencies, making them ideal for sequential tasks while requiring fewer computational resources than traditional RNNs.

All models are trained on preprocessed textual data (tokenized and padded) and evaluated using accuracy as the primary metric.

---

## Model Performance

| Model | Accuracy (%) |
|-------|---------------|
| CNN   | 88.95         |
| RNN   | 82.99         |
| GRU   | 88.53         |

**Conclusion**: 
The CNN model achieved the highest accuracy at 88.95%, demonstrating its strength in capturing local patterns and features from text data.

The GRU model also performed very well, with an accuracy of 88.53%, showcasing its ability to retain important information over longer sequences, though slightly less effective than CNN in this case.

The RNN model, while effective for sequence-based tasks, lagged behind with 82.99% accuracy, highlighting its limitations in handling longer dependencies compared to GRU and CNN.

**In conclusion, CNN is the most suitable model for this sentiment analysis task, followed closely by GRU.**
