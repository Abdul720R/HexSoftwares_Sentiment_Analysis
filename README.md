# HexSoftwares_Sentiment_Analysis
# Sentiment Analysis Using RNN, LSTM, and GRU

## 🔥 Project Overview

This project implements a sentiment analysis system using deep learning in Python. It classifies text reviews as Positive or Negative. Three types of models are explored:

* Simple RNN
* Bidirectional LSTM
* GRU

Key features include data preprocessing, model training, evaluation, and live predictions.
---

## 🚀 Features

* Cleans and preprocesses text (lowercasing, stopword removal, stemming).
* Tokenizes and pads text sequences for neural network input.
* Implements three deep learning architectures with dropout and layer normalization:
   RNN, LSTM, GRU
* Uses early stopping to prevent overfitting.
* Evaluates performance with:
   Accuracy & loss curves
   Confusion matrix
   Classification report (Precision, Recall, F1-score)
* Live sentiment prediction function for any input text.
* Saves trained models and tokenizer for future use.

---

## 📂 Dataset

* train.ft.txt.bz2 and test.ft.txt.bz2
* Each line format: __label__<0/1> <review text>
* Labels converted to binary: 0 = Negative, 1 = Positive

---
