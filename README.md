# tfidf
Program to find term weight (term X doc) matrix based on tf-idf score.
Author: Manu Madhavan
Email: mmnamboodiry@gmail.com

Disclaimer
This Program use python 2.7
This program does not consider stemming, and punctuation removal.
TF is normalized by the count of highest freqent term in the document
idf is caluclated as log(N/(1+n)) where N is the total no of docs and n is the number of docs in which term appears.
intermediate results are written to seperate files.
The corpus consists of documents seperated by new line.

The folder contain following files:

Source File
tfidf.py- Source program

Inputs
corpus.txt Sample corpus
stopwords.lst list of stop words

Output:
termFreq.txt
idf.txt
term_weight.txt

To run:
$python tfidf.py
