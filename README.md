# Movie_review_classification

Three are three parts for this project. 

Part 1:
This corpus vocabulary is what would represent the content of each different document for clustering and classification purposes, 
which will be our next step. This means that we need to make decisions - what is in, what is out. To decide on whether or not we will keep a term, we need to know that:
It is important, in at least one (preferably more) documents, and
It is prevalent, in at least two or three of the documents.

Use some of NLP text mining techniques to clean the text.
- remove punctuation
- lower case
- remove tags
- remove special chars and digits
- lemmatization
- remove stop words

Calculate the TF-IDF score to find the most popular term in the dataset. Use Word2vec to calcuate the word vectors. calculate the cosine similarity across corpus using TFIDF matrix.



Part 2:

Clustering:

Used K-means and TF-IDF to create clustering model to identify the movies in the same genres. Manipulating the number of k to get the best k-means model


Sentiment Analysis:
Use the class corpus and do sentiment analysis for the positive and negative reviews. Use SVM, logistic, naive bayers and random forest to predict the positive and negative reviews

Topic Modeling:

Use the entire class corpus. Try LSA and LDA methods to do topic modeling, on the class corpus. Manipulating the number of topics to get the best model performance


Create ontology knowledge graph to identify the relationship between each entity
