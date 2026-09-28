# NLP Text Preprocessing

## Overview

This project demonstrates fundamental **NLP preprocessing techniques** using Python and NLTK. It covers the main steps used to transform raw text into a more structured form for downstream NLP and machine learning tasks.

## Tasks

### 1. Tokenization

Demonstrates tokenization at two levels:

* **Sentence Tokenization** — splits text into individual sentences.
* **Word Tokenization** — splits text into individual tokens.

**Library:** NLTK

### 2. Regular Expressions

Uses Python's `re` module to identify and remove common text noise, including:

* URLs
* Special characters
* Numbers
* Extra spaces

### 3. Stop Words Removal

Uses NLTK's English stop-word vocabulary to filter out frequent words that may provide limited information for certain NLP tasks.

### 4. Stemming vs. Lemmatization

Compares two text normalization techniques:

* **Stemming** — reduces words by removing or modifying word endings.
* **Lemmatization** — reduces words to their dictionary-based base form.

**Tools:** `PorterStemmer` and `WordNetLemmatizer`

### 5. Comprehensive Preprocessing Pipeline

Combines multiple preprocessing techniques into a single workflow:

```text
Raw Text
   ↓
Text Cleaning
   ↓
Tokenization
   ↓
Stop Words Removal
   ↓
Stemming / Lemmatization
   ↓
Processed Text
```

This mini-project demonstrates how different preprocessing steps can be combined to prepare text for further NLP processing and machine learning tasks.

## Concepts Covered

* Text preprocessing
* Tokenization
* Regular Expressions
* Stop Words
* Stemming
* Lemmatization
* NLP preprocessing pipelines

## Technologies

* Python
* NLTK
* Regular Expressions (`re`)