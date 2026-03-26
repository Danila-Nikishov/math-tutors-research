# 📊 Math Tutors Research

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Status](https://img.shields.io/badge/Status-Research-yellow.svg)

This repository contains an end-to-end pipeline for solving a **multilabel classification task** using fully connected neural networks.

A detailed description of the methodology, experiments, and results is available in the [`report.pdf`](report.pdf).

---

## 🚀 Technologies & Tools

- **Tokenization:** BPE, Unigram (SentencePiece)  
- **Embeddings:** Word2Vec (Gensim), Navec  
- **Framework & Language:** TensorFlow, Python  

---

## 📂 Key Components

### 🗂️ Data
Contains datasets used for training and evaluation:
- Raw and preprocessed text datф  
- Train/test splits  
- Auxiliary metadata (if applicable)

---

### 🔤 Tokenization
Implements text preprocessing and subword tokenization:
- BPE and Unigram models (SentencePiece)  
- Generated vocabularies  
- Tokenized corpuses  

---

### 🧠 Embeddings
Handles vector representations of text:
- Pretrained Navec embeddings  
- Self-made Word2Vec embeddings  

---

### 📓 Notebooks

- [`parsing.ipynb`](parsing.ipynb) — data downloading and parsing  
- [`EDA.ipynb`](EDA.ipynb) — data analysis and preprocessing  
- [`tokenization.ipynb`](tokenization/tokenization.ipynb) — data tokenization 
- [`embeddings.ipynb`](embeddings/embeddings.ipynb) — creating different embeddings
- [`neural_networks.ipynb`](neural_networks.ipynb) — training neural networks  

---
