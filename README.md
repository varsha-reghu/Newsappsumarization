# Newsappsumarization


# 📰 News Article Summarization

## 📌 Project Overview

This project demonstrates how to automatically summarize lengthy news articles using Natural Language Processing (NLP). The objective is to generate concise, human-readable summaries that retain the core meaning of the original article. We used the pretrained transformer model `t5-small` from Hugging Face for abstractive summarization and showcased the workflow in a Jupyter Notebook.

---

## 🧠 Features

- Pretrained T5 model (`t5-small`) for summarization
- Abstractive summarization approach (not just copy-pasting key phrases)
- Preprocessing pipeline including text cleaning
- Easily extendable to other transformer models or datasets
- Visual comparison of original articles and generated summaries

---

## 📁 Files

- `NewsArticleSummarization.ipynb`: Main notebook with code, outputs, and explanations
- *(Optional)* `sample_articles.csv`: Dataset of news articles (not included unless specified)
- *(Optional)* `requirements.txt`: List of Python dependencies

---

## ⚙️ How to Run

1. Clone the repository or download the `.ipynb` file.
2. Open the notebook in [Google Colab](https://colab.research.google.com/) or your local Jupyter Notebook.
3. Install required libraries (if running locally):
   ```bash
   pip install transformers torch
