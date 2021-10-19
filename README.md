# plantbased-patty-sentiment-analysis
See full writeup: https://lindsaytubbstech.com/portfolio_projects/project2.html

Plant-based alternatives to meat have become a staple on supermarket shelves and restaurant menus. This trend has been bolstered by the increasing popularity of veganism and sustainable diets, as well as significant product innovations. Gone are days of veggie burgers bearing no resemblance to burgers made with beef. The plant-based patties of today, primarily produced by Impossible Foods and Beyond Meat, claim to be nearly identical to the real deal in appearance, texture, and taste. As these alternatives steadily gain popularity and eat up the meat industry’s market share, I am curious about public opinion towards these products.

Social media is an arbiter of public opinion, and I chose Twitter as a channel. With a focus on tweets containing the terms “impossible burger” or “beyond burger”, I obtained 40,000 recent tweets for each term.

Goals:
<ol>
  <li>Get 40,000 tweets (30,000 to train machine learning model, 10,000 to test machine learning model) for both "impossible burger" and "beyond burger" search terms</li>
  <li>Create training sets by analyzing tweets for positive (0) or negative (1) sentiment using a rule-based method called <a href="https://github.com/nltk/nltk/blob/develop/nltk/sentiment/vader.py">VADER</a></li>
  <li>Visualize positive and negative training sets of tweets in word clouds to gain familiarity with each set</li>
  <li>Compare combinations of feature extraction methods (Bag-of-Words and TF-IDF) and machine learning models (Logistic Regression, XGBoost, Decision Trees) to find the combination with the highest F1 score</li>
  <li>Train machine learning model using features extracted from training sets of tweets</li>
  <li>Apply trained machine learning model to predict sentiments of tweets in test sets</li>
</ol>

Scripts:
<ol>
  <li>Get tweets: twitter_scraper.ipynb</li>
  <li>Create training sets: make_training_set.ipynb</li>
  <li>Impossible Burger: Impossible Twitter Sentiment Analysis.ipynb</li>
  <li>Beyond Burger: Beyond Twitter Sentiment Analysis.ipynb</li>
</ol>

Resources:

https://github.com/JustAnotherArchivist/snscrape

https://github.com/nltk/nltk

Hutto, C.J. & Gilbert, E.E. (2014). VADER: A Parsimonious Rule-based Model for
Sentiment Analysis of Social Media Text. Eighth International Conference on
Weblogs and Social Media (ICWSM-14). Ann Arbor, MI, June 2014.

https://github.com/scikit-learn/scikit-learn

https://github.com/dmlc/xgboost

https://github.com/amueller/word_cloud

https://github.com/pandas-dev/pandas

https://github.com/numpy/numpy

https://github.com/matplotlib/matplotlib
