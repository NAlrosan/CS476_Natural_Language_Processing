# Byte Pair Encoding (BPE) From Scratch

## 📌 Overview

This mini-project implements **Byte Pair Encoding (BPE)** from scratch in Python. BPE is a subword tokenization technique widely used in modern Natural Language Processing (NLP) systems.

The notebook first explains the BPE algorithm and then implements the core merge process programmatically. It also applies the implementation to a real dataset from **Hugging Face** and visualizes the learned merge operations.

## 🎯 Objectives

- Understand how Byte Pair Encoding works.
- Implement BPE without relying on a pre-built tokenizer.
- Learn how frequent symbol pairs are identified and merged.
- Apply the tokenizer to a real-world text dataset.
- Visualize the sequence of merge operations.

## 🧠 Key Concepts

- Subword tokenization
- Vocabulary construction
- Pair-frequency counting
- Iterative merging
- Tokenization of unseen words
- Hugging Face datasets

## 🛠️ Technologies

- Python
- Jupyter Notebook / Google Colab
- `collections`
- `re`
- Hugging Face `datasets`

## 🔄 Workflow

1. Prepare a small text corpus.
2. Represent words as sequences of characters/symbols.
3. Count adjacent symbol-pair frequencies.
4. Select the most frequent pair.
5. Merge the pair.
6. Repeat the process for the required number of merges.
7. Apply the implementation to a real dataset.
8. Inspect and visualize the resulting merges.

## 📂 Files

- `Naif_BPE_From_Scratch_stu.ipynb` — Complete implementation and experiments.
- `README.md` — Project documentation.

## ▶️ How to Run

1. Open the notebook in Jupyter Notebook or Google Colab.
2. Install the required dependencies.
3. Run the cells from top to bottom.
4. For the real-dataset section, make sure internet access is available so the Hugging Face dataset can be loaded.

## 💡 Takeaway

This project demonstrates the mechanics behind subword tokenization and provides a from-scratch implementation of an important NLP technique used in modern language models.
