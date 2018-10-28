# Information Retrieval System using TF-IDF

The objective of this project is to implement an information retrieval system which uses TF-IDF to present the search results which are most relevant to the query.
The IR system will get a search query from the user and the response will be "n" number of results ordered from most relevant to least.
As this is an IR system, diversity in vocabulary is required on a document to document basis. NLP preprocessing may be required like stemming and lemmatizations to identify a specific word and categorize the documents to the root word. Same preprocessing is applied to queries and the words are used to calculate TF-IDF and "n" documents with the highest scores are presented in descending order.

The paper compares the naive word frequency method to TF-IDF method for information retrieval. 
[Using TF-IDF to Determine Word Relevance in Document Queries](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.121.1424&rep=rep1&type=pdf)
