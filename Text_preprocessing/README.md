# Text Preprocessing in NLP

## 📌 Overview

This mini-project is a practical exploration of **text preprocessing techniques used in Natural Language Processing (NLP)**.

Using movie-review text, the notebook demonstrates how raw text can be cleaned and normalized before being used in downstream NLP tasks.

## 🎯 Objectives

- Understand why text preprocessing is important.
- Clean noisy text data.
- Compare different preprocessing techniques.
- Experiment with NLTK and spaCy.
- Prepare text for machine learning and NLP applications.

## 🧹 Techniques Covered

### Lowercasing
Converts text into a consistent lowercase representation.

### HTML Tag Removal
Uses regular expressions to remove HTML elements from text.

### URL Removal
Removes web addresses such as `https://...` and `www...`.

### Punctuation Removal
Removes punctuation characters using Python string utilities.

### Chat Word Handling
Expands common abbreviations such as chat/slang terms into their full forms.

### Spelling Correction
Uses TextBlob to experiment with correcting misspelled words.

### Stopword Removal
Uses NLTK stopword lists to remove common words that may not provide useful information for some NLP tasks.

### Emoji Handling
Demonstrates both removing emojis and converting emojis into text using the `emoji` library.

### Tokenization
Compares word and sentence tokenization using:
- NLTK
- spaCy

### Stemming
Uses the Porter Stemmer to reduce words to simplified stems.

### Lemmatization
Uses WordNet Lemmatizer to convert words toward their dictionary/base forms.

## 📊 Dataset

The notebook works with the **IMDB Dataset of 50K Movie Reviews**.

The original notebook references the dataset from Kaggle.

## 🛠️ Technologies

- Python
- Pandas
- Regular Expressions
- NLTK
- spaCy
- TextBlob
- emoji

## 🔄 Workflow

1. Load the movie-review dataset.
2. Inspect sample reviews.
3. Apply individual preprocessing techniques.
4. Test each technique on example sentences.
5. Apply selected techniques to the dataset.
6. Compare different NLP preprocessing approaches.

## 📂 Files

- `Text_Preprocessing_in_NLP.ipynb` — Main notebook.
- `README.md` — Project documentation.

## ▶️ How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload or provide the IMDB dataset.
3. Install the required libraries.
4. Download the required NLTK resources.
5. Run the cells sequentially.

## 💡 Takeaway

Text preprocessing is a fundamental stage of NLP. This project provides hands-on experience with cleaning, normalization, tokenization, stemming, lemmatization, and other techniques used to transform raw language into usable NLP data.
