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

**Conclusion**: The CNN model slightly outperforms the others in terms of accuracy, followed closely by GRU. RNN performs well but is comparatively less accurate for this task.

