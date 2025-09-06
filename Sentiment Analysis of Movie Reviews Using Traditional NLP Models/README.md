Sentiment Analysis of Movie Reviews Using Traditional NLP Models

[Sentiment Analysis of Movie Reviews Using Traditional NLP Models](https://github.com/raulmejia000/Data_projects_TripleTen/blob/main/Sentiment%20Analysis%20of%20Movie%20Reviews%20Using%20Traditional%20NLP%20Models/Sentiment%20Analysis%20of%20Movie%20Reviews%20Using%20Traditional%20NLP%20Models%20Project%2014.ipynb)

Introduction

In this project, I applied machine learning techniques for text classification to analyze sentiment in movie reviews. The goal was to determine whether a review is positive or negative, using traditional Natural Language Processing (NLP) models. This project builds on concepts of feature extraction, preprocessing, and supervised learning, focusing on accuracy and interpretability over raw deep learning models.

What Was Done

Data Preparation
- Loaded and cleaned a dataset of movie reviews with associated sentiment labels.
- Performed preprocessing such as tokenization, lowercasing, and stopword removal.
- Transformed the raw text into numerical features using Bag of Words (CountVectorizer) and TF-IDF.

Modeling
- Trained several traditional machine learning models including:
    - Logistic Regression
    - Naïve Bayes
    - Support Vector Machine (SVM)
    - Random Forest
- Compared performance across models using accuracy, precision, recall, and F1-score.

Evaluation
- Conducted k-fold cross-validation to ensure stability of results.
- Created confusion matrices to analyze classification errors.
- Identified key words and features most influential in predicting sentiment.

Tools & Libraries Used
Python, pandas, numpy, scikit-learn, matplotlib, seaborn, nltk.

Project Features (Screenshots)

Below are some visual outputs from the analysis:

Distrubtion of Ratings

Number of reviews of different polarites per year as well as distrubtion of different polarities per movie


Results & Conclusion
- Logistic Regression and SVM achieved the highest accuracy among all models.
- Naïve Bayes was fast and interpretable but performed slightly worse on recall.
- Random Forest underperformed compared to linear models, highlighting that traditional bag-of-words features are better suited for linear classifiers.
- Overall, Logistic Regression with TF-IDF features was the most effective approach, achieving strong accuracy and balanced precision/recall.

Improvements & Business Suggestions

Improvements:
- Incorporate advanced text preprocessing such as lemmatization and n-grams.
- Experiment with hyperparameter tuning (GridSearchCV) for improved performance.
- Add deep learning baselines (e.g., LSTM, BERT) for comparison.

Business Outcomes:
- A reliable sentiment analysis system can help companies analyze customer feedback at scale (e.g., movie reviews, product reviews, support tickets).
- By detecting trends in positive/negative sentiment, companies can quickly adapt marketing strategies and improve customer satisfaction.
- Insights from word importance can highlight what aspects of a product or service customers care about most.
