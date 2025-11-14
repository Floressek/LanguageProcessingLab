# LanguageProcessingLab

This repository contains laboratory work for the Natural Language Processing (NLP) course. Jupyter notebooks demonstrate practical implementations of various NLP techniques and methods using Python libraries such as NLTK, scikit-learn, and spaCy.

## About This Project

A comprehensive collection of Natural Language Processing laboratory exercises exploring text processing, linguistic analysis, and statistical methods. The project includes hands-on implementations of fundamental NLP concepts including text preprocessing, frequency analysis, TF-IDF vectorization, POS tagging, morphological analysis, and document similarity metrics using both English and Polish language corpora.

## Folder Structure

```
LanguageProcessingLab/
├── Lab1/          # Text sourcing, preprocessing, and statistical analysis
├── Lab2/          # POS tagging and morphological analysis
├── Lab3/          # Laboratory 3 notebooks
├── Lab4/          # Laboratory 4 notebooks
└── Lab5/          # Laboratory 5 notebooks
```

## Lab Descriptions

### Lab 1: Text Processing Fundamentals and Statistical Analysis

This laboratory introduces fundamental NLP techniques and statistical text analysis:

1. **Text Sourcing**
   - Downloading books from Project Gutenberg and Wolne Lektury
   - Building text corpora from multiple literary sources
   - Using the requests library for data acquisition

2. **Text Preprocessing**
   - Removing stopwords using NLTK
   - Filtering non-alphanumeric characters
   - Text normalization and lowercasing
   - Creating clean, processed corpora

3. **Word Frequency Analysis and Zipf's Law**
   - Computing word frequencies using CountVectorizer
   - Creating frequency distribution plots
   - Verifying Zipf's law on selected documents
   - Understanding power law distributions in natural language

4. **TF-IDF (Term Frequency-Inverse Document Frequency)**
   - Building TF-IDF matrices using TfidfVectorizer
   - Understanding term importance across documents
   - Feature extraction for document comparison

5. **Document Similarity Analysis**
   - Computing cosine similarity between document pairs
   - Creating similarity matrices for corpus analysis
   - Identifying most and least similar documents

6. **Dimensionality Reduction with PCA**
   - Applying Principal Component Analysis to high-dimensional text data
   - Visualizing documents in 2D space
   - Understanding document relationships through visualization

### Lab 2: Part-of-Speech Tagging and Morphological Analysis

This laboratory focuses on linguistic analysis and morphological features:

1. **Text Sourcing**
   - Collecting Polish language books from Wolne Lektury
   - Building a Polish language corpus for morphological analysis

2. **POS Tag Frequency Analysis (2a)**
   - Computing frequency of part-of-speech tags
   - Visualizing POS tag distributions
   - Understanding syntactic structure of texts

3. **Detailed Morphological Tag Analysis (2b)**
   - Analyzing detailed morphological features
   - Examining gender, case, number, and other grammatical categories
   - Statistical analysis of morphological complexity

4. **Noun Lemmatization and Frequency Analysis (3)**
   - Extracting nouns from Polish texts
   - Lemmatization to base forms
   - Computing and visualizing noun frequencies
   - Understanding lexical richness in literary texts

5. **TF-IDF with Word Cloud Visualization (4)**
   - Applying TF-IDF to nouns
   - Creating word cloud visualizations
   - Identifying key thematic terms in documents

6. **Semantic Ambiguity Analysis (5)**
   - Identifying polysemy and homonyms in texts
   - Examples of lexical ambiguity
   - Disambiguation strategies and approaches

7. **Subject-Verb Relationship Analysis (6)**
   - Finding nouns in subject positions
   - Identifying verbs in predicate relationships
   - Analyzing subject-verb collocations
   - Understanding syntactic dependencies

### Lab 5: Fine tuning bert-distilbert models with amazon-review sentiment analysis

> Model on hugginhface: https://huggingface.co/Floressek/sentiment_classification_from_distillbert

## Technologies Used

- **Python 3.x**
- **NLTK** - Natural Language Toolkit for text processing
- **scikit-learn** - Machine learning library for TF-IDF and PCA
- **spaCy** - Industrial-strength NLP for morphological analysis
- **pandas** - Data manipulation and analysis
- **matplotlib/seaborn** - Data visualization
- **wordcloud** - word cloud generation
- **requests** - HTTP library for downloading texts

## Usage

Each lab folder contains:
- Jupyter notebooks (.ipynb files) with complete implementations
- Detailed explanations and comments
- Visualizations and analysis results
- Any supporting files or data required for the lab

To run the notebooks:
1. Install required dependencies: `pip install nltk scikit-learn spacy pandas matplotlib seaborn wordcloud requests`
2. Download necessary NLTK data: `python -m nltk.downloader all`
3. Install Polish language model for spaCy: `python -m spacy download pl_core_news_sm`
4. Open notebooks in Jupyter Lab or Google Colab
5. Execute cells sequentially to reproduce the analysis

Notebooks are uploaded after each lab session to demonstrate completion and understanding of the course material.
