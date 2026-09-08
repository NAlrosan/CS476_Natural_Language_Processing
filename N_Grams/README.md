# N-Gram Language Model with NLTK

## 📌 Overview

This mini-project implements a simple **trigram language model** using Python and the NLTK Reuters corpus.

The model learns the probability of a word occurring based on the two words that precede it and can then predict the most likely next word.

## 🎯 Objectives

- Understand N-gram language models.
- Generate bigrams and trigrams from text.
- Calculate conditional word probabilities.
- Build a simple next-word prediction function.
- Experiment with the NLTK Reuters corpus.

## 🧠 Key Concepts

- Unigrams
- Bigrams
- Trigrams
- Conditional probability
- Language modeling
- Next-word prediction

## 🛠️ Technologies

- Python
- NLTK
- Reuters corpus
- `collections.defaultdict`

## 🔄 Workflow

1. Download the Reuters corpus and required NLTK tokenization resources.
2. Load and tokenize the text.
3. Generate trigrams.
4. Count how often each third word occurs after a pair of words.
5. Convert frequency counts into probabilities.
6. Select the most probable next word.
7. Test the model with an example context.

## 📂 Files

- `N_Grams_NLTK.ipynb` — Main notebook.
- `README.md` — Project documentation.

## ▶️ How to Run

1. Open the notebook in Jupyter Notebook or Google Colab.
2. Install/download the required NLTK resources.
3. Run the notebook cells in order.
4. Test the `predict_next_word()` function with different word pairs.

## 💡 Takeaway

This project demonstrates the basic mechanics of statistical language modeling and shows how word context can be used to predict the next word in a sequence.
