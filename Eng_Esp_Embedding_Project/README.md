# Cross-Lingual English–Spanish Word Embedding Model

## 📌 Overview

This project develops and evaluates **cross-lingual English–Spanish word embedding models**. The notebook experiments with multiple embedding approaches to represent words and sentences in vector space and compare semantic relationships across English and Spanish.

Several Word2Vec configurations are trained and evaluated, including word-level and character-level approaches.

## 🎯 Objectives

- Build English–Spanish embedding models.
- Compare CBOW and Skip-gram architectures.
- Explore word-level and character-level representations.
- Measure semantic similarity using cosine similarity.
- Evaluate embeddings at both word and sentence levels.
- Experiment with translation and transformer-based representations.

## 🧠 Models & Methods

### Word2Vec
- CBOW Word2Vec
- Skip-gram Word2Vec

### Character-Level Models
- Character-level CBOW
- Character-level Skip-gram

### Additional NLP Components
- Cosine similarity
- Sentence embeddings
- PCA
- t-SNE
- Google Translate
- BERT-based representations
- MarianMT translation models

## 🛠️ Technologies

- Python
- PyTorch
- Gensim
- NLTK
- SciPy
- Scikit-learn
- Hugging Face Transformers
- Google Colab

## 🔄 Workflow

1. Install the required dependencies.
2. Load and preprocess the English–Spanish dataset.
3. Prepare the text for embedding training.
4. Train word-level CBOW and Skip-gram models.
5. Train character-level CBOW and Skip-gram models.
6. Load previously trained models when required.
7. Evaluate word-level semantic similarity.
8. Evaluate sentence-level similarity.
9. Visualize embeddings using dimensionality-reduction techniques.
10. Compare the different embedding approaches.

## 📊 Example Evaluation

The notebook includes cosine-similarity evaluations between sentences. Example recorded similarities include values such as **0.7907, 0.8530, 0.9297, 0.9386, 0.9135, and 0.8842**, demonstrating the use of vector similarity to evaluate semantic relationships.

## 📂 Files

- `NLP_Eng_Esp_Embedding_Model.ipynb` — Main project notebook.
- `README.md` — Project documentation.

## ▶️ How to Run

1. Open the notebook in Google Colab or Jupyter.
2. Install the required Python packages.
3. Provide the required dataset.
4. Run the preprocessing and training sections.
5. Run the evaluation sections to reproduce the similarity experiments.

> **Note:** The notebook contains Google Drive integration for saving and loading trained models.

## 💡 Takeaway

This project provides practical experience with multilingual representation learning and shows how different embedding architectures can be compared for cross-lingual semantic similarity.
