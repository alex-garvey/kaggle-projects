## Natural Language Processing with Disaster Tweets
### Description:
#### "In this competition, you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. You’ll have access to a dataset of 10,000 tweets that were hand classified."
### Steps followed:
#### 1) Preprocess data
#### 2) Split training data into train/validation sets
#### 3) Index the vocabulary in the training set
#### 4) Retrieve word embeddings pre-trained on twitter data and create a word-to-vector dictionary
#### 5) Create the embedding matrix
#### 6) Build and train the model (Input -> Embedding -> LSTM -> Dropout -> Dense)
#### 7) Generate predictions

Note: as this was my first NLP project, I relied heavily on the examples found here: https://keras.io/examples/nlp/pretrained_word_embeddings/
