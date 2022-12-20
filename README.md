The goal of this supervised ML project is to classify a text news as "Fake" or "Real" using LogisticRegression model.

**Data:**
 * Kaggle's Fake News dataset. 
 * It contains over 20k observations across 5 column (Id, Title, Author, Text and Label)
 * The datasest has been retrieved to Google collab notebook using Kaggle's API.
 
**Steps & Modules:**
 * pandas - for data pre-processing and EDA 
 * nltk's stopwords - to filter out stopwords
 * nltk's PorterStemmer - to stem words of selected features to root words by defining a function
 * sklearns's Tfidfvectorizer - to convert the text data into machine understandable vectors (numbers)
 * sklearn's train_test_split - to split the data into training and test set
 * sklearns's LogisticRegression - to train the classification model
 * sklearn's accuracy_score - to validate model accuracy
