# PRODIGY_DS-04
Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards trending topics and popular entities.

##  Objective

This project aims to explore how users express opinions on Twitter. The sentiment of tweets is classified into:
- ✅ Positive  
- ❌ Negative  
- 😐 Neutral  
- 🤷‍♂️ Irrelevant (ignored in modeling)


## Steps Performed

1. **Data Cleaning**
   - Removed URLs, mentions (@), hashtags (#), special characters
   - Converted all text to lowercase
   - Removed common English stopwords

2. **EDA & Visualization**
   - Sentiment distribution bar chart
   - Word clouds for positive and negative tweets
   - Entity-level sentiment breakdown (top 10 entities)

3. **Feature Engineering**
   - TF-IDF vectorization of cleaned tweets

4. **Modeling**
   - Trained a **Logistic Regression classifier**
   - Evaluated using accuracy, precision, recall, and F1-score


## Output Samples
Sentiment Distribution
 <img width="585" height="387" alt="Sentiment Distribution" src="https://github.com/user-attachments/assets/58249705-e302-42e9-ba1d-80a57f5bfd0a" />

Entity Sentiment Breakdown
<img width="1184" height="578" alt="Sentiment Breakdown" src="https://github.com/user-attachments/assets/f96bb0e1-6c29-4526-919e-befd4ec54cf7" />



##  Key Insights

- Entities like brands or public figures have a mixed sentiment profile.
- Positive tweets frequently contain expressive adjectives.
- Logistic Regression performs well with TF-IDF on short text.
- Text cleaning and normalization significantly impact model accuracy.


##  Tech Stack

- Python 3.11
- Pandas & Matplotlib
- Seaborn & WordCloud
- scikit-learn
- NLTK for text cleaning


##  Getting Started

1. Download the dataset from: [Kaggle Twitter Sentiment Dataset](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)
2. Place it inside the `data/` folder as `twitter_training.csv`
3. Open and run `notebooks/sentiment_analysis.ipynb` step-by-step


