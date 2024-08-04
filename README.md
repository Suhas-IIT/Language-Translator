# Language Translator Project

## Introduction

The objective of this project is to develop a neural machine translation system capable of translating sentences between English and Hindi. This system leverages a Long Short-Term Memory (LSTM) network, a type of recurrent neural network (RNN) well-suited for sequence-to-sequence learning tasks.

The project consists of three main components:

1) Data Preparation: The dataset.py script handles the loading and preprocessing of the dataset. This includes tokenizing the sentences, creating vocabulary sets, and preparing the data in a format suitable for training the LSTM models.

2) Model Training: The Training LSTM for Translation.ipynb notebook contains the implementation of the LSTM models for translation. It includes the model architecture, training loop, and evaluation metrics. The model is trained on a dataset of English-Hindi sentence pairs, optimizing for translation accuracy.

3) Translation System: The translate.py script implements the translation system. It defines a Translate class with methods for training the model, saving and loading model weights, and translating sentences. The script demonstrates the end-to-end process of training the model and performing translations, showcasing the practical application of the developed system.

The resulting translation system provides a foundation for further development and refinement, with potential applications in language learning, cross-language communication, and multilingual information retrieval.
