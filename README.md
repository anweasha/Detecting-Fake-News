# Detecting-Fake-News

We often come across fake news in our daily lives through various forms of social media or even while interacting with people. As such, here I have tried to build a python project to detect fake news. I have made use of a news dataset to train the model and then ultimately to test its accuracy.

### Dataset
[news dataset](https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view)

### Terms related to this project

> TfidfVectorizer
- TF (Term Frequency): The number of times a word appears in a document is its Term Frequency.
- IDF (Inverse Document Frequency): IDF is a measure of how significant a term is in the entire corpus.
The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.

> PassiveAggressiveClassifier  
- PassiveAggressiveClassifier is such an online learning algorithm whose purpose is to make updates that correct the loss, causing very little change in the norm of the weight vector.

### Steps
1. Loading the dataset
2. Splitting it into train and test sets
3. Building a TfidfVectorizer on it
4. Initializing a PassiveAggressive Classifier
5. Fitting the model
6. Calculation the accuracy of the model
7. Building a confusion matrix
