# Natural-Language-Processing-Sentiment-Analysis

### In this project, IMDB dataset contains 4 data files, i.e., “x_train.csv”, “y_train.csv”, “x_test.csv” and "y_test.csv". The first file contains several thousand single-sentence reviews collected from three domains: imdb.com, amazon.com, yelp.com.The files “y_train.csv”, contain the labels of training data and “x_test.csv” contains 600 single-sentence reviews that you can use as test data and "y_test.csv" contains labels of test data that can be used to evalue the performance of the models.

#### Each review consists of a sentence and a binary label indicating the emotional sentiment of the sentence (1 for reviews expressing positive feelings; 0 for reviews expressing negative feelings). 

#### Data is loaded from csv files. All the punctuations are removed and uppercase in reviews are converted to lowercase.

#### Bag of Words representation has been used to extract features from the text data i.e., reviews.

#### After Model hyperparameter tuning, training is performed on SVM and Naive Bayes models to classify the positive and negative reviews.
