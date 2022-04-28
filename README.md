# seq2seqTextClassification

#In this Deep Learning Project, we will use the customer complaints data about consumer financial products to build multi-class text classification models using RNN and LSTM.

Problem Overview

Text Classification is one of the essential applications of Natural Language Processing. Neural network-based methods have obtained significant progress on various natural language processing tasks. As deep learning is emerging, training complex data has become faster and easier with networks like RNNs and LSTM.

In the previous projects, we have witnessed how to use the Naïve Bayes algorithm for text classification, and we have also implemented the skip-gram model for word embeddings. This project will see how to implement the Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) models for text classification.

 

 

Aim

To perform text classification on the dataset using RNN and LSTM models.

 

 

Data Description

The dataset contains more than two million customer complaints about consumer financial products. Amongst the various available columns, we have a column that contains the actual text of the complaint and one column containing the product for which the customer is raising the complaint.

 

 

Tech Stack

Language: Python
Libraries:  pandas, torch, nltk, numpy, pickle, re, tqdm, sklearn
 

Prerequisite

The torch framework
Multiclass Text Classification using Naive Bayes in Python
Skip Gram Model Python Implementation for Word Embeddings
 

Approach

Installing the necessary packages through pip command
Importing the required libraries
Defining configuration file paths
Process glove embeddings
Read the text file
Convert embeddings to float array
Add embeddings for padding and unknown items
Save embeddings and vocabulary
Process Text data
Read the CSV file and drop the null values
Replace duplicate labels
Encode the label column and save the encoder and encoded labels
Data Preprocessing
Conversion to lower case
Punctuation removal
Digits removal
Additional spaces removal
Tokenization
Building Data loader
Model Building
RNN architecture
LSTM architecture
Train function
Test function
Model training
RNN model
LSTM model
Prediction on Test data
