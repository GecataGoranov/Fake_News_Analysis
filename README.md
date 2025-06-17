# Fake News Analysis (EDA and Linguistic Feature Extraction)

This project explores the distinction between **real** and **fake news** using **exploratory data analysis (EDA)** and **linguistic feature extraction**. The analysis focuses on understanding key characteristics of fake news, including text length, sentiment, readability, and lexical diversity. The notebook can be seen by clicking the following binder button:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GecataGoranov/Fake_News_Analysis)

## Overview

The project answers the following questions:
1. What linguistic features distinguish real news from fake news?
2. How do sentiment and emotional tone differ between real and fake news?
3. What features can help in identifying fake news?

## Tools and Libraries
- **Python**, **pandas**, **matplotlib**, **seaborn**, **nltk**, **spaCy**, **textstat**, **WordCloud**

## Datasets
- **Fake News Dataset**: A Kaggle dataset with articles labeled as **real** (0) and **fake** (1).
- **ISOT Fake News Dataset**: Contains **true** and **fake** articles for analysis.

## Project Structure

### 1. Data Preparation
- **Cleaning**: Handled missing values, removed articles with empty text, and merged datasets.

### 2. Exploratory Data Analysis (EDA)
- Compared **text** and **title lengths** between real and fake news.
- Analyzed **frequent words** and visualized them via **word clouds**.
- Conducted **bi-gram analysis** to explore common word pairs.

### 3. Feature Extraction
- **POS tagging** to analyze linguistic patterns (e.g., nouns, verbs, adjectives).
- **Readability scores** using the Flesch Reading Ease formula.
- **Lexical diversity** and **sentiment analysis** for further insights.

## Key Findings
- Fake news articles tend to be shorter but share similar lexical diversity and readability with real news.
- Keywords like "Clinton" appear more often in fake news, suggesting potential biases.
- **Sentiment** analysis shows emotional differences, with fake news often being more sensational.

## Conclusion

This project provided a deep dive into **text analysis** and **NLP techniques** to distinguish real from fake news. While it doesn't include machine learning models, it sets the stage for more advanced work in **fake news detection**.

### Note
This project was completed as a **beginner** in data science, focusing on **feature extraction** and **exploratory analysis** as part of my learning process.

## Future Work
- Add **machine learning models** to classify news articles.
- Experiment with **advanced NLP** techniques like **transformers** and **BERT** for more accurate fake news detection.
