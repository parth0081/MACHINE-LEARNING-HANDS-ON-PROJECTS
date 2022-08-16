*Spam emails* also referred to as spam are junk emails. They are sent in bulk for commercial purposes. Spam emails can also be dangerous. It can include malicious links that can infect your computer with malware or phishing attacks.

* This is a project I am working on while learning concepts of data science and machine learning. The goal here is to identify whether an email is spam or ham. We will take a dataset of labeled email messages and apply classification techniques. We can later test the model for accuracy and performance on unclassified email messages. *
Dataset which is used in this project can be found in the Data folder in this repository.

I found some problems in reading this file as well because it has problems with the encoding so we have to specify the encoding here as 'Latin-1'. Then we take only those feature which are required and dropping all other features. Only 'email' and 'label' columns were remaining.

I have done some of the steps as followed:

a) Basic Text Preprocessing- Removing Punctuations and Special Characters from the text and lowering the text.

b) Advanced Text Processing- Stemming and lemmatization and then removing stopwords.

c) Tokenization- Tokenization can separate sentences, words, characters, or subwords. When we split the text into sentences, we call it sentence tokenization. For words, we call it word tokenization.

d) Vectorisation- Two methods are applied to vectorisation - Bag of Words (BOW) and Tf-Idf (Term Frequency–Inverse Document Frequency).

e) Modelling- In this project, i have applied Naive-Bayes Classifier: Gaussian Naive Bayes and Multinomial Naive Bayes Classifier.


* Finally we get the accuracy scores like- *

*STEMMING*

0.9748803827751196-----> MultinomialNB Tf-Idf stemming


0.8636363636363636-----> GaussianNB Tf-Idf stemming


0.8660287081339713-----> GaussianNB BOW stemming


0.9760765550239234-----> MultinomialNB BOW stemming


*Lemmatizer*

0.9736842105263158-----> Mulltinomial Tf-Idf Lemmatizer


0.8851674641148325-----> GaussianNB Tf-Idf Lemmatizer


0.8863636363636364-----> GaussianNB BOW Lemmatizer


0.9736842105263158-----> Multinomial BOW Lemmatizer

