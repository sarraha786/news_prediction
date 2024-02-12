# news_prediction

 Your task is to predict whether a news article is real or fake using the available information.


1. You should pre-process your text using at least some of the steps outlined in lectures (e.g. normalizing to lowercase, splitting into words, etc.).


2. You should split the resulting combined dataframe into training and testing datasets OR use cross-validation.  If you go the splitting-into-training-and-testing route, we recommend an 80-20 split (i.e. training gets 80% of the data; testing gets 20%) and use the testing dataset to report your accuracy score.  If you go the cross-validation route, we recommend using 5-fold cross-validation and use the mean accuracy score for your 5 folds when reporting your accuracy score.

3. As as final challenge, we would like you to attempt to characterize each of the datasets in terms of their semantic content.  This might involve extracting the most commonly occurring words (possibly limiting that to specific parts of speech), examining the Named Entities, and extracting keywords by leveraging word embeddings.  Use your imagination, and remember there is no single "correct" answer.  For those of you looking to teach yourself something new, check out Latent Dirichilet Allocation (LDA) using the `gensim` library.  To get started with LDA, check out https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/ and https://radimrehurek.com/gensim/models/ldamodel.html.  You are not required to use LDA, but it is a powerful technique for extracting topics from text.
