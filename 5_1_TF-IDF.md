# TF-IDF
TF-IDF is a method which gives us a numerical weightage of words which reflects how important the particular word is to a document in a corpus. A corpus is a collection of documents. <mark> <b>Tf is Term frequency </b></mark>, and <mark> <b> IDF is Inverse document frequency. </b></mark> This method is often used for information retrieval and text mining.

### Term Frequency * Inverse Document Frequency
In a simple language, TF-IDF can be defined as follows:

A High weight in TF-IDF is reached by a high term frequency(in the given document) and a low document frequency of the term in the whole collection of documents.

TF-IDF algorithm is made of 2 algorithms multiplied together.

### Term Frequency
Term frequency (TF) is how often a word appears in a document, divided by how many words there are.

    TF(t) = (Number of times term t appears in a document) / (Total number of terms in the document)

### Inverse document frequency
Term frequency is how common a word is, inverse document frequency (IDF) is how unique or rare a word is.

    IDF(t) = log_e(Total number of documents / Number of documents with term t in it)