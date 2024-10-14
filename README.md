# TextGenerationRNN
1) Description:
    This project implements a text generation model using Recurrent Neural Networks (RNN) on a Wikipedia article about "The Solar System" to generate text based on word and character sequences.

2) Key Features:
  Data Preprocessing: Lowercased text, removed special characters, tokenized words, removed stopwords, and applied lemmatization.
  Embedding: Used pre-trained GloVe embeddings (100-dimensional).
  Word-based Model: 4 SimpleRNN layers with dropout.
  Character-based Model: 4 SimpleRNN layers with dropout.
  Training: 100 epochs, batch size of 256.
  Generated Output: Text predictions using word and character models.

4) Programming Tools:
   Python, TensorFlow/Keras, NLTK, Gensim, Wikipedia API.
