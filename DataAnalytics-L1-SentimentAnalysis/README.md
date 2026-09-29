# IMDB Movie Reviews — Sentiment Analysis

## Project Overview
This project builds a machine learning model that classifies movie reviews as positive or negative, using the IMDB Dataset of 50K Movie Reviews.

## Dataset
Source: [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) (Kaggle). Not included in this repo due to file size — download from the link above.

## Steps Performed
1. **Data Loading** — 50,000 reviews, perfectly balanced (25,000 positive / 25,000 negative).
2. **Text Preprocessing** — lowercased text, removed HTML tags and punctuation, removed stopwords, applied lemmatization.
3. **Feature Extraction** — TF-IDF Vectorizer (5,000 features).
4. **Train/Test Split** — 80/20 split, stratified by sentiment.
5. **Model Training** — trained two classifiers: Naive Bayes and Logistic Regression.
6. **Evaluation** — accuracy, precision, recall, F1-score, and confusion matrices for both models.
7. **Visualization** — sentiment distribution bar chart, WordClouds for positive/negative reviews.
8. **Error Analysis** — reviewed 5 misclassified examples to identify patterns (mixed opinions, lost negation words, sarcasm).

## Results

| Model | Accuracy | Precision | Recall | F1-score |
|---|---|---|---|---|
| Naive Bayes | 0.8531 | 0.8489 | 0.8592 | 0.8540 |
| Logistic Regression | 0.8883 | 0.8811 | 0.8978 | 0.8894 |

**Best model: Logistic Regression** — outperformed Naive Bayes on every metric.

## Files
- `sentiment_analysis.ipynb` — full notebook with code and outputs
- `sentiment_distribution.png` — class balance chart
- `confusion_matrix_naive_bayes.png`
- `confusion_matrix_logistic_regression.png` (file: `logistic regression.png`)
- `README.md` — this file

## Tools Used
Python, pandas, NLTK, scikit-learn, matplotlib, seaborn, wordcloud, Jupyter Notebook

## Author
Alluru Varshini
