# Sentiment Analysis with Logistic Regression

## 📌 Overview

This mini-project builds a **sentiment analysis classifier** for movie reviews using TF-IDF features and Logistic Regression.

The notebook uses an IMDB sentiment dataset from Hugging Face, performs text preprocessing, converts reviews into numerical TF-IDF vectors, trains a Logistic Regression classifier, and evaluates its predictions.

## 🎯 Objectives

- Prepare movie-review text for NLP.
- Remove unnecessary text elements through preprocessing.
- Convert text into numerical features using TF-IDF.
- Train a Logistic Regression sentiment classifier.
- Evaluate classification performance.
- Predict the sentiment of new reviews.

## 📊 Dataset

The notebook loads:

`damerajee/IMDB-sentiment-reviews`

from Hugging Face.

For the demonstration in the notebook, **100 samples** are selected using a fixed random seed.

## 🔄 Workflow

1. Load the IMDB sentiment dataset.
2. Convert the dataset into a Pandas DataFrame.
3. Explore sentiment and review-length distributions.
4. Clean and preprocess the reviews.
5. Split the data into training and testing sets using an 80/20 split.
6. Convert reviews into TF-IDF vectors.
7. Train a Logistic Regression classifier.
8. Evaluate the model using:
   - Accuracy
   - Classification report
   - Confusion matrix
9. Test the trained model on a new movie review.

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Hugging Face Datasets

## 🤖 Model

The main classifier is:

**Logistic Regression + TF-IDF**

TF-IDF represents words according to their importance within the collection of reviews, while Logistic Regression performs the binary sentiment classification.

## 📂 Files

- `SA_Log_Regression.ipynb` — Main sentiment-analysis notebook.
- `README.md` — Project documentation.

## ▶️ How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required dependencies.
3. Run the NLTK resource-download cells.
4. Load the Hugging Face dataset.
5. Execute the notebook cells in order.
6. Modify the sample size if you want to train on more than the 100 demonstration samples.

## 💡 Takeaway

This project demonstrates a complete traditional NLP classification pipeline, from raw movie reviews to preprocessing, TF-IDF feature extraction, supervised learning, evaluation, and inference.
