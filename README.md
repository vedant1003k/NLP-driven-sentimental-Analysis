# sentiment-analysis-of-movie-reviews


The code implements sentiment analysis using the Naive Bayes algorithm on the Movie Reviews corpus provided by the NLTK library. The corpus contains 2146 movie reviews,
categorized as either positive or negative. The code uses 1900 reviews for training and 1900 reviews for testing. It extracts 3000 most common words from the reviews as 
features, and uses them to create a feature set for each review. The Naive Bayes classifier is trained on the feature sets, and its accuracy is evaluated using the testing 
set. Finally, the trained classifier is saved to a file using Python's pickle module.


# Build (Windows)

git clone git@github.com:vedant1003k/sentiment-analysis-of-movie-reviews.git
