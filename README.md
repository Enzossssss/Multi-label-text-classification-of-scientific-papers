# Multi-label-text-classification-of-scientific-papers

Multi-label classification of scientific articles.

Article texts are first processed via this text processing pipeline: lower case -> tokenization -> remove stopwords -> lemmatization (or stemming) -> remove punctuation.

Then document representation is performed via: TF-IDF and Bag Of Words (BOW).

First an attempt at classification is made with the following machine learning methods: SVC, (Multinomial) Naive Bayes and Logistic Regression.

Then via a BiLSTM trying out GloVe Embeddings and Word2Vec.

And finally through the use of the BERT-Base Transformers.

All these approaches are then compared at the end of the notebook.
