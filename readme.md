# Extractive Text Summarization from Scratch for News Articles
Text summarization is the process of reducing a text Document in order to create a summary that retains
the most important points of the original document. As The problem of information overload has grown, 
and the quantity of data has increased, so has interest in automatic summarization. 
It is very difficult for human beings to manually summarize large documents of text. 
Text Summarization methods can be classified into extractive and abstractive summarization.
We have used an extractive summarization method consists of selecting important sentences, paragraphs etc. 
from the original News Articles and concatenating them into shorter form. 
The importance of sentences is decided based on cosine distance of sentence vectors, similarity matrix and generating the 
scores using text rank algorithm. Extractive methods work by selecting a subset of existing words, phrases, or sentences in 
the original text to form the summary. The extractive summarization systems are typically based on techniques for sentence 
extraction and aim to cover the set of sentences that are most important for the overall understanding of a given News Article.

## Repository
Contains the complete python code,dataset used , report and presentation as well.

## Reference
Code is inspired by "Edubey" article @ Medium.
Bhanot, K. (n.d.). Different techniques to represent words as vectors (Word Embeddings). Retrieved from towardsdatascience.com: https://towardsdatascience.com/different-techniques-to-represent-words-as-vectors-word-embeddings-3e4b9ab7ceb4
Dhaji, H. (n.d.). Text Summarization-Key Concepts. Retrieved from Medium: https://medium.com/@harshdarji_15896/text-summarization-key-concepts-23df617bfb3e
Edmonson. (n.d.). http://courses.ischool.berkeley.edu/i256/f06/papers/edmonson69.pdf.
Garbade, D. M. (n.d.). a-quick-introduction-to-text-summarization-in-machine-learning-3d27ccf18a9f. Retrieved from https://towardsdatascience.com: https://towardsdatascience.com/a-quick-introduction-to-text-summarization-in-machine-learning-3d27ccf18a9f
Luhun. (n.d.). http://courses.ischool.berkeley.edu/i256/f06/papers/luhn58.pdf.
Prateek, J. (n.d.). An Introduction to Text Summarization using the TextRank Algorithm. Retrieved from https://www.analyticsvidhya.com/: https://www.analyticsvidhya.com/blog/2018/11/introduction-text-summarization-textrank-python/
Rada Mihalcea, P. T. (2004). TextRank: Bringing Order into Text. Retrieved from https://www.semanticscholar.org: https://www.semanticscholar.org/paper/TextRank%3A-Bringing-Order-into-Text-Mihalcea-Tarau/7b95d389bc6affe6a127d53b04bcfd68138f1a1a
