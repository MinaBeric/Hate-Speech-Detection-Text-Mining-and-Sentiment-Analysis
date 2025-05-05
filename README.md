# Hate-Speech-Detection-Text-Mining-and-Sentiment-Analysis

This project focuses on the development of an automated system for detecting hate speech using deep learning models, specifically **BiLSTM** (Bidirectional Long Short-Term Memory) and **BERT** (Bidirectional Encoder Representations from Transformers). The goal is to classify text sentences as hate or noHate.

## Dataset

The dataset used in this project is available at the following link:

[Click here to access the dataset](https://github.com/Vicomtech/hate-speech-dataset)

## Models Used

1. **BiLSTM**: A deep learning model that uses bidirectional LSTMs for sequential data processing. This model helps capture context from both past and future words in a sentence.
2. **BERT**: A transformer-based model that excels in understanding the context of words in a sentence. BERT's attention mechanism allows it to consider the entire sentence, making it more effective in tasks like text classification.

## Project Overview

The project consists of the following steps:

1. **Data Preprocessing**: The dataset is cleaned and preprocessed for deep learning models. This includes tokenization, text normalization, and removal of any irrelevant information.
2. **Model Training**: The models (BiLSTM and BERT) are trained on the preprocessed dataset to detect hate speech effectively.
3. **Evaluation**: The models are evaluated based on various metrics such as accuracy, precision, recall, and F1-score to determine the best-performing model.

## Installation

To run this project, you will need Python 3.x and the following libraries:

- TensorFlow / PyTorch (for deep learning models)
- Transformers (for BERT implementation)
- Numpy
- Pandas
- Scikit-learn
- Matplotlib (for visualization)

Install the required dependencies using:

```bash
pip install -r requirements.txt
