# word2vec
word2vec is an algorithm for constructing vector representations of words, also known as word embeddings. The vector for each word is a semantic description of how that word is used in context, so two words that are used similarly in text will get similar vector represenations. Once you map words into vector space, you can then use vector math to find words that have similar semantics.


> gensim provides a nice Python implementation of Word2Vec that works perfectly with NLTK corpora. The model takes a list of sentences, and each sentence is expected to be a list of words. This is exactly what is returned by the sents() method of NLTK corpus readers. So let’s compare the semantics of a couple words in a few different NLTK corpora:



