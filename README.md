# Reviews-Classifier-NLP
### Implement Natural Language Processing to classify reviews.
## Introduction
### This is to classify Yelp Reviews into 1 star or 5 star categories based off the text content in the reviews.

## [Yelp Review Data Set](https://www.kaggle.com/c/yelp-recsys-2013).

Each observation in this dataset is a review of a particular business by a particular user.

The "stars" column is the number of stars (1 through 5) assigned by the reviewer to the business. (Higher stars is better.) In other words, it is the rating of the business by the person who wrote the review.

The "cool" column is the number of "cool" votes this review received from other Yelp users. 

All reviews start with 0 "cool" votes, and there is no limit to how many "cool" votes a review can receive. In other words, it is a rating of the review itself, not a rating of the business.

## Steps invovled

- Import the modules, dependencies and load the dataset.
- Analyse the dataset, get shape,info and check for null values and balance of the dataset.
- Do Exploratory Data Analysis and data visualization.
- Slice the data into features and label.
- Create a analyzer(function) for Text Normalization.
  - Tokenization - split text into list of words.
  - Stopwords exclusion - remove punctuations and Stopwords.
  - Stemming - transform each word in text into its base form (lemma).
- Split the data into training and testing datasets.
- Create Pipeline with vectorization and classifier as sequence of operations.
  - Perform vectorization using analyzer.
- Train the models and compare the models.

## Conclusion
Tfidf transformer decreased the accuracy.
Achieved good accuracy without fitting tfidf transformer.
Classified reviews using Natural Language Processing.
