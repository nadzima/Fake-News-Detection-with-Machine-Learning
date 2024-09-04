# 📰 Fake News Detection with Machine Learning 🤖

Welcome to the **Fake News Detection** project! This project uses machine learning to classify news articles as either **Real** or **Fake**. 🕵️‍♂️🔍

<img src="https://media.giphy.com/media/Q7SKqn3G97xpmfSOvG/giphy.gif" alt="fake-news" width="50%">

## 🔎 Dataset Overview

The dataset comes from Kaggle's **[Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)**.

### 📂 What's Inside?

- **Fake.csv**: Contains fake news articles 📰🚫.
- **True.csv**: Contains real news articles 📰✅.

## 🛠️ Project Structure

- **FakeNewsClassification.ipynb**: Jupyter notebook with all the code for detecting fake news 🧑‍💻.
- **README.md**: This file! 📖
  
## 🔧 Project Pipeline

1. **Data Preprocessing** 🛠️
   - The data was cleaned by removing unwanted characters, tokenizing the text, and applying techniques like lemmatization.
   
2. **Text Vectorization** 🧠
   - We utilized **word embeddings** via `Tokenizer` from `tensorflow.keras.preprocessing.text` to convert text into numerical sequences for modeling.
   
3. **Modeling** 🧬
   - Various machine learning and deep learning models were used to classify the news, including LSTM and RNN architectures. The models were trained on sequences of tokenized words to identify patterns and make predictions.

## Source and Documentation

This project is part of a Guided Project on Coursera. The documentation and implementation follow the instructions provided during the course. You can learn more about the Guided Projects on Coursera here:
[Fake News Detection with Machine Learning](https://www.coursera.org/projects/nlp-fake-news-detector?)
