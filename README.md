# Sentimental-Analysis

This repository talks about applying the Sentimental-Analysis based on the Customer's feedback using Machine Learning classification based algorithm and Natural Language Processing, thus identifying whether feedback given is positive or negative. Further a comparative analysis was done by applying both TF-IDF Vectorization bag of words and Word2Vec Embedding technique on to the review.csv files.
TF-IDF stands for “Term Frequency – Inverse Document Frequency.” It reflects how important a word is to a document in a collection or corpus. This technique is often used in information retrieval and text mining as a weighing factor.
The Term Frequency is termed as The number of times a word appears in a document divided by the total number of words in that document.
![image](https://user-images.githubusercontent.com/63364350/116404231-12b89680-a84c-11eb-9925-25058a2a3743.png)

The term Inverse Document Frequency is termed as the logarithm of the number of the documents in the corpus divided by the number of documents where the specific term appears.
![image](https://user-images.githubusercontent.com/63364350/116404365-2f54ce80-a84c-11eb-800a-7d49ab6c5ebe.png)
Hence TF-IDF is finally Composed as 
![image](https://user-images.githubusercontent.com/63364350/116404417-3845a000-a84c-11eb-8eae-06508a690d1d.png)

It was found that the word2vec techniques better accuracy rate of 84%, when compared with the TF-IDF technique which seems to have approximately 80 to 82%. 
