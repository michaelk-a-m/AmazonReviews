# Amazon Reviews Sentiment Analysis
Using spaCy as the natural language processing tool, this project aims to perform sentiment analysis using Amazon Reviews dataset on Mobile Electronic products.
SpaCy library is used to clean, tokenise, and lemmatise the text before transforming the reviews to bag of words and TF-IDF.

To simplify the project, the neutral reviews are filtered out and the star ratings are converted into either positive or negative sentiment.
The bag of words and TF-IDF vectors will then be feed into a Logistic Regression to train and evaluate.
