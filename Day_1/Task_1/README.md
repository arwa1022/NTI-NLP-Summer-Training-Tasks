# NLP Text Classification — Rule-Based Examples

## Overview

This project demonstrates two basic **NLP text classification** tasks using Python and predefined vocabulary rules:

* **Sentiment Classification** — classifies a review as positive, negative, or neutral.
* **Spam Detection** — classifies an email as spam or not spam based on keyword matching.

The exercises provide a simple introduction to **text preprocessing, vocabulary matching, and rule-based classification**.

## Sentiment Classification

The sentiment classifier uses predefined positive and negative vocabularies and counts their occurrences in a review.

The classification is determined by comparing the number of positive and negative words:

* More positive words → Positive
* More negative words → Negative
* Equal counts → Neutral

## Spam Detection

The spam filter uses a predefined vocabulary of spam-related keywords.

It counts the matching keywords in an email and applies a predefined threshold to determine whether the email should be classified as spam.

## Concepts Covered

* Text normalization
* Basic tokenization
* Keyword matching
* Vocabulary-based classification
* Rule-based NLP
* Sentiment analysis
* Spam detection
* Classification thresholds

## Technologies

* Python
* Basic NLP concepts
* Rule-based text classification