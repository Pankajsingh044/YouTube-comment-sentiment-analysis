# YouTube-Comment-Sentiment-Analysis

## 📌 Project Overview

This project focuses on **sentiment analysis of YouTube comments** using Natural Language Processing (NLP) and Machine Learning techniques.

The system processes YouTube comments, cleans and normalizes the text, performs text preprocessing, extracts linguistic features, and classifies comments into three sentiment categories:

- 🟢 Positive
- ⚪ Neutral
- 🔴 Negative

The project also analyzes **code-mixed and multilingual comments**, including English, Hindi, and Gujarati language tokens.

## 🎯 Objectives

- Analyze YouTube comments.
- Clean and preprocess raw comment text.
- Remove unnecessary characters and noise.
- Normalize text for NLP processing.
- Analyze sentiment distribution.
- Classify comments into Positive, Neutral, and Negative categories.
- Analyze multilingual and code-mixed comments.
- Identify frequently occurring words.
- Generate visualizations for exploratory data analysis.

## 📊 Dataset

The dataset contains YouTube comments along with information such as:

- Comment ID
- Video ID
- Author
- Comment Text
- Like Count
- Published Date
- Code-Mixing Information
- Token Counts
- Sentiment Label

### Dataset Statistics

- **Original comments:** 21,729
- **Final processed comments:** 21,701
- **Sentiment classes:** Positive, Neutral, Negative

## 🧹 Data Preprocessing

The following preprocessing steps are performed:

1. Load the dataset.
2. Identify the comment/text column.
3. Identify the sentiment column.
4. Remove empty comments.
5. Remove duplicate comments.
6. Clean the text.
7. Normalize text.
8. Process emojis and special characters.
9. Tokenize comments.
10. Analyze language-specific tokens.
11. Generate processed text.

## 📈 Sentiment Distribution

| Sentiment | Comments |
|-----------|----------|
| Positive  | 12,702 |
| Neutral   | 7,681 |
| Negative  | 1,318 |
| **Total** | **21,701** |

## 🌐 Multilingual & Code-Mixed Analysis

The project analyzes language characteristics within YouTube comments, including:

- English tokens
- Hindi tokens
- Gujarati tokens
- Other tokens
- Code-mixed comments
- Code-Mixing Index (CMI)

This helps understand how users combine multiple languages while commenting on YouTube.

## 🔍 Exploratory Data Analysis

The project includes:

- Sentiment distribution analysis
- Comment length analysis
- Word frequency analysis
- Token analysis
- Code-mixing analysis
- Language distribution
- Data visualization

## 🔤 Word Frequency Analysis

Frequently occurring words are extracted from the processed comments to understand common terms used by users.

## 🛠️ Technologies Used

```text
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Natural Language Processing (NLP)
Machine Learning
