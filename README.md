# PRODIGY_DS_04 - Sentiment Analysis on Social Media

This repository contains my submission for Task-04 of the Data Science Internship at **Prodigy InfoTech**.

## Task Description

Analyze and visualize sentiment patterns in social media data (Twitter) to understand public opinion and attitude toward specific trends or brands.

## Dataset

- `twitter_training.csv`
- Columns: `UserID`, `Trend`, `Sentiment`, `Text`

## Key Steps

1. **Text Preprocessing:**
   - Removed URLs, mentions, hashtags using regex
   - Lowercased text, removed punctuation and stopwords
   - Applied stemming using `PorterStemmer`

2. **EDA & Visualization:**
   - Distribution of sentiments (Positive, Negative, Neutral)
   - Word frequency analysis by sentiment
   - WordClouds for visual representation

3. **Feature Engineering:**
   - Vectorized text using `CountVectorizer` and `TF-IDF`

4. **Modeling:**
   - Built basic models like Naive Bayes and Logistic Regression
   - Evaluated model accuracy and performance

## Tools Used

- Python
- Pandas, NumPy
- NLTK (for text processing)
- Matplotlib, Seaborn, WordCloud
- Scikit-learn

## Outcome

Understood the power of sentiment analysis in gauging public opinion on social platforms and practiced applying natural language processing techniques for real-world applications.

---

**Internship**: Prodigy InfoTech  
**Task**: PRODIGY_DS_04 - Social Media Sentiment Analysis
