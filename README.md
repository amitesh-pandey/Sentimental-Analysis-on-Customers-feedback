# Sentimental-Analysis

This repository talks about applying the Sentimental-Analysis based on the Customer's feedback using Machine Learning classification based algorithm and Natural Language Processing, thus identifying whether feedback given is positive or negative. Further a comparative analysis was done by applying both TF-IDF Vectorization bag of words and Word2Vec Embedding technique on to the review.csv files.

TF-IDF stands for “Term Frequency – Inverse Document Frequency.” It reflects how important a word is to a document in a collection or corpus. This technique is often used in information retrieval and text mining as a weighing factor.
The Term Frequency is termed as The number of times a word appears in a document divided by the total number of words in that document.
![image](https://user-images.githubusercontent.com/63364350/116404525-57443200-a84c-11eb-96b6-a46f16ca864c.png)

The term Inverse Document Frequency is termed as the logarithm of the number of the documents in the corpus divided by the number of documents where the specific term appears.
![image](https://user-images.githubusercontent.com/63364350/116404594-6aef9880-a84c-11eb-82ee-70cbbb98fcf4.png)

Hence TF-IDF is finally Composed as:

![image](https://user-images.githubusercontent.com/63364350/116404621-704ce300-a84c-11eb-9493-1c6202a579e1.png)

Word2Vec is a two-layer neural net that processes text by “vectorizing” words. Its input is a text corpus and its output is a set of vectors: feature vectors that represent words in that corpus.A word embedding is a learned representation for text where words that have the same meaning have a similar representation. It is this approach to representing words and documents that may be considered one of the key breakthroughs of deep learning on challenging natural language processing problems.

It was found that the word2vec techniques provides a better accuracy rate of 84%, when compared with the TF-IDF technique which seems to have approximately 80 to 82%. 
