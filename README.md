# Part 3 - NLP and Sequence Modeling Mini Project

## Project Overview

This project focuses on Natural Language Processing (NLP) and sequence modeling techniques for text classification.

The objective of the project is to:
- preprocess customer support text data
- convert text into numerical representations
- build a baseline NLP classification model
- understand sequence-based deep learning models such as LSTMs

The dataset contains customer support messages along with sentiment labels.

---

## Dataset Understanding

The dataset includes:
- customer messages
- sentiment labels
- communication channels
- additional support-related information

The text data was explored by analyzing:
- class distribution
- sample text records
- average text length
- text length distribution

---

## Text Preprocessing

The following preprocessing steps were applied:
- converting text to lowercase
- removing special characters
- removing unnecessary symbols
- stopword removal

Text preprocessing helps improve text quality and allows models to focus on meaningful information.

---

## Text Vectorization

TF-IDF vectorization was used to convert text into numerical form for the baseline machine learning model.

TF-IDF helps identify important words in the dataset while reducing the impact of very common words.

---

## Baseline NLP Model

A Logistic Regression model was used as the baseline classifier.

The model was evaluated using:
- accuracy score
- confusion matrix
- classification report

This provided a strong baseline for comparison with sequence-based deep learning models.

---

## Sequence Model using LSTM

An LSTM-based sequence model was created to learn sequential relationships between words.

The sequence model contains:
- tokenizer-based sequences
- embedding layer
- LSTM layer
- dense output layer

LSTMs help capture contextual information and long-term dependencies in textual data.

---

## Attention and Transformers

The project also explored:
- limitations of RNNs
- advantages of LSTMs
- attention mechanisms
- transformer architectures

These concepts are important in modern NLP and generative AI systems.

---

## Key Learnings

This project helped in understanding:
- NLP preprocessing workflow
- TF-IDF vectorization
- text classification
- sequence modeling
- LSTM architecture
- attention mechanisms
- transformer-based NLP systems

---

## Repository Structure

```text
part-3-nlp-sequence-modeling/
│
├── dataset/
├── results/
├── notebook.ipynb
├── README.md
└── requirements.txt
```

---

## Dataset Source

Dataset provided as part of the assignment dataset package.
