# Suicide-Prevention-by-Early-Detection

# Suicide Detection by Twitter Dataset using ChatGPT and Other ML Models

## Overview
This project utilizes advanced machine learning models, including ChatGPT for natural language processing (NLP), to identify and classify tweets based on the presence of suicidal ideation. By analyzing tweet content, this initiative aims to contribute to early intervention and support for individuals displaying signs of distress on social media platforms.

## Dataset Description
The dataset comprises tweets with a wide range of topics, emotions, and expressions, classified into two categories:

- **Not Suicide Post:** Tweets that do not express any suicidal sentiments or intentions.
- **Potential Suicide Post:** Tweets exhibiting indications of suicidal thoughts, feelings, or intentions.

### Columns
- **Tweet:** Contains the text content of the tweets.
- **Suicide:** Provides annotations indicating the classification of the tweets as either 'Not Suicide Post' or 'Potential Suicide Post'.

## Models Used
We employ several machine learning models to analyze and classify the tweets:

- `GaussianNB` (Gaussian Naive Bayes)
- `BernoulliNB` (Bernoulli Naive Bayes)
- `RandomForestClassifier` (Random Forest)
- `GradientBoostingClassifier` (Gradient Boosting)
- `XGBClassifier` (XGBoost)
- `BaggingClassifier` (Bagging)
- `AdaBoostClassifier` (AdaBoost)

These models were selected for their strengths in text data analysis and classification tasks.

## Requirements
- Python 3.x
- Scikit-learn
- XGBoost
- NLTK or spaCy
- Pandas
- Numpy

Refer to `requirements.txt` for a detailed list of dependencies.

## Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/yourgithubusername/suicide-detection-twitter.git
cd suicide-detection-twitter
pip install -r requirements.txt
