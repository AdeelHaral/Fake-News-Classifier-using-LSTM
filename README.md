**Fake News Classifier using LSTM**

**Overview**

This project implements a Fake News Classifier using deep learning techniques, specifically Long Short-Term Memory (LSTM) networks. The model is trained on a dataset obtained from Kaggle, which contains labeled examples of both fake and real news articles.


**Key Concepts and Technologies**

**1. Data Preparation**

Dataset: The dataset used in this project is sourced from Kaggle, containing labeled news articles as either fake or real. Ensure the dataset is appropriately preprocessed and split into training and testing sets.

Text Preprocessing: Utilize Pandas for data manipulation and preprocessing. Numpy is employed for numerical operations. Text data is tokenized, and sequences are padded for input into the LSTM model.

**2. LSTM Model with Keras**

Deep Learning Framework: TensorFlow and Keras are employed to build a sequential LSTM model for text classification.

Embedding Layer: The model starts with an Embedding layer to represent words as dense vectors.

LSTM Layers: Multiple LSTM layers are used to capture sequential dependencies in the text data.

Dense Layer: A Dense layer with a sigmoid activation function produces the final output for binary classification.

**3. Tokenization and Padding**

One-Hot Encoding: Convert the text data into one-hot encoded sequences to represent words numerically.

Pad Sequences: Ensure all sequences have the same length by padding shorter sequences, necessary for input into the LSTM model.

**4. Training and Evaluation**
   
Model Compilation: The model is compiled with appropriate loss and optimizer functions.

Model Training: Fit the model to the training data and validate on a separate validation set.

Model Evaluation: Assess model performance using metrics such as accuracy, precision, recall, and F1-score.

**Dependencies**
Pandas
Numpy
TensorFlow
Keras
Re
nltk

