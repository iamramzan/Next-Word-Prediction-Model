# Next-Word-Prediction-Model
Project Overview:

In this project, I build a Next Word Prediction model using Deep Learning.

Project Steps:

- importing packages and dataset
- tokenize the text
- create input-output pairs by splitting the text into sequences of tokens
- pad the input sequences
- split the sequences into input and output
- convert the output to one-hot encode vectors
- build a neural network architecture
- compile and train the model
- generate the next word predictions

Local Setup:

- import numpy as np
- import tensorflow as tf
- from tensorflow.keras.preprocessing.text import Tokenizer
- from tensorflow.keras.preprocessing.sequence import - pad_sequences
- from tensorflow.keras.models import Sequential
- from tensorflow.keras.layers import Embedding, LSTM, Dense
