Overview

This project explores the use of n-gram language models for text generation. Specifically, it covers bigram, trigram, and quadgram models, which predict the next word in a sequence based on the previous 1, 2, or 3 words, respectively. The primary focus is on calculating probabilities for n-grams, sampling the next word, and generating text using these probabilities.

Key Features

Bigram Model: Predicts the next word based on the previous single word.

Trigram Model: Predicts the next word based on the previous two words.

Quadgram Model: Predicts the next word based on the previous three words.

Text Generation: Generates a sequence of words using the probabilities from the n-gram models.

Probability Calculations: Counts occurrences of n-grams in the dataset and computes the probabilities of the next word.

Datasets Used

The models are built and tested on a corpus provided in the notebook. The dataset should be a list of tokenized sentences, where each sentence is a list of words.

Example format:

corpus = [
    ["this", "is", "a", "sample"],
    ["this", "is", "another", "example"]
]

How to Run the Code

Install Dependencies: Ensure you have Python installed. The required libraries include random and collections, which are part of Python's standard library.

Prepare the Corpus: Replace the placeholder corpus with your tokenized text data.

Run the Script:

Save the Python file as Assignment1_Massimo_Ridella.py.

Run the script in your terminal or preferred IDE using:

python Assignment1_Massimo_Ridella.py

Use the Models:

To generate text using bigrams:

generate_text_from_bigram("word1", "word2", 20)

To generate text using trigrams:

generate_text_from_trigram("word1", "word2", 20, trigram_probs)

To generate text using quadgrams:

generate_text_from_quadgram("word1", "word2", "word3", 20, quadgram_probs)

File Structure

Assignment1_Massimo_Ridella.py: The main Python file containing all functions and logic for n-gram modeling and text generation.
