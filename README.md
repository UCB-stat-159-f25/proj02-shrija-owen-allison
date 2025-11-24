[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/7TPcE591)
# Project 02 - Reproducibility in Natural Language Processing 

This is the Stat 159/259 Fall 2025 Project 2 submission for Allison Nguyen, Shrija Malla, and Owen Hill. 

## Binder

## Description 

This project analyzes the full collection of U.S. Presidential State of the Union (SOTU) addresses from 1790–2024 and builds a fully reproducible natural language processing (NLP) workflow. The analysis proceeds through four main stages:

### Part 1: Data Loading & Initial Exploration

We load the SOTU dataset using pandas, inspect metadata such as presidents, years, and document lengths, and compute preliminary descriptive statistics to understand how the corpus is structured.

### Part 2: Text Preprocessing with spaCy & TF–IDF

We implement a complete spaCy-based pipeline including tokenization, lemmatization, stopword removal, and punctuation filtering. We compare word frequencies across documents and use TF–IDF vectorization to represent speeches numerically for further analysis.

### Part 3: LDA and BERTopic Topic Modeling

We apply two major topic modeling methods:

1. LDA (Latent Dirichlet Allocation) to identify word-based co-occurrence topics using a traditional bag-of-words representation.

2. BERTopic, a modern transformer-based method that uses BERT embeddings, UMAP dimensionality reduction, HDBSCAN clustering, and c-TF-IDF to produce semantically coherent topics.

We compare the two approaches, interpret clusters, and visualize results using pyLDAvis and BERTopic’s interactive plotting tools.

### Part 4: Open Ended Exploration

## Notes:
1. The dataset is sourced from Kaggle: (https://www.kaggle.com/datasets/nicholasheyerdahl/state-of-the-union-address-texts-1790-2024)
2. The outputs folder contains all figures generated from parts 1-4. Figures in a static form are saved as a png while interractive ones are saved as an HTML file
