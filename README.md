# README for Assignment1_Massimo_Ridella

## Overview
This project explores the use of n-gram language models for text generation. Specifically, it covers bigram, trigram, and quadgram models, which predict the next word in a sequence based on the previous 1, 2, or 3 words, respectively. The primary focus is on calculating probabilities for n-grams, sampling the next word, and generating text using these probabilities.

## Key Features
- **Bigram Model**: Predicts the next word based on the previous single word.
- **Trigram Model**: Predicts the next word based on the previous two words.
- **Quadgram Model**: Predicts the next word based on the previous three words.
- **Text Generation**: Generates a sequence of words using the probabilities from the n-gram models.
- **Probability Calculations**: Counts occurrences of n-grams in the dataset and computes the probabilities of the next word.

## Dataset Used
The dataset used for this project is **Act 2 Scene 2 of Macbeth**, provided as a string file.

## How to Run the Code

### Step 1: Install Dependencies
Ensure you have Python installed. The required libraries include:
- `random`
- `collections`

Both are part of Python's standard library, so no additional installations are needed.

### Step 2: Run the Script
1. Save the Python file as `Assignment1_Massimo_Ridella.py`.
2. Run the script in your terminal or preferred IDE using:
   ```bash
   python Assignment1_Massimo_Ridella.py
   ```

### Step 3: Use the Models
You can use the following functions to generate text:

- **Bigram Model**:
  ```python
  generate_text_from_bigram("word1", "word2", 20)
  ```
  Generates 20 words starting from the bigram `("word1", "word2")`.

- **Trigram Model**:
  ```python
  generate_text_from_trigram("word1", "word2", 20, trigram_probs)
  ```
  Generates 20 words starting from the trigram `("word1", "word2")` using precomputed trigram probabilities.

- **Quadgram Model**:
  ```python
  generate_text_from_quadgram("word1", "word2", "word3", 20, quadgram_probs)
  ```
  Generates 20 words starting from the quadgram `("word1", "word2", "word3")` using precomputed quadgram probabilities.

## File Structure
- **`Assignment1_Massimo_Ridella.py`**: The main Python file containing all functions and logic for n-gram modeling and text generation.

## Survey Results
![image alt](https://github.com/massimorid/NLP_Ass1/blob/main/Survey%20Results_%20AI%20Model%20Performance%20in%20Imitating%20Shakespeare.png?raw=true)
