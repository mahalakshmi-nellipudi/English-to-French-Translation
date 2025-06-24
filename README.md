# English-to-French-Translation
This project implements an English-to-French language translator using a deep learning-based sequence-to-sequence (Seq2Seq) model with LSTM layers. The model is trained on bilingual sentence pairs and is capable of generating basic French translations from English input.
 Features:
-Text preprocessing and cleaning (tokenization, padding)
-Encoder-Decoder architecture using Keras LSTM
-Trained on a real English–French parallel corpus
-Handles start/end tokens to structure sentence prediction
-Supports translation of short and medium-length sentences

Tech Stack:
-Python
-TensorFlow / Keras
-NumPy, Pandas
-Google Colab (for training and experimentation)

Dataset:
The model is trained on 30,000 English–French sentence pairs from the Tatoeba Project, sourced from manythings.org.
