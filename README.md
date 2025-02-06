# NLP-Text-Classification-Twitter-and-WhatsApp-analysis-

How we can analyze a text in social media such as Twitter or WhatsApp or how Amazon and other public online store analyze the reaction of people to the quality of each production? 

In NLP (natural language processing), text can be analyzed and classified. The process of text classification is as following: 

1-	Tokenization 

a.	Tokenizing the string 

b.	Lowercasing 

c.	Removing stop words and punctuation

2-	Normalization

a.	Stemming 

b.	Lemmatizing 

3-	Changing text to number (numerical data)

a.	Bag of words 

b.	TFIDF 

4-	Classification: 

a.	Preprocessing 

b.	Defining classifier

5-	Evaluation 

6-	Feature selections or permutations

7-	Discussion and suggestions 

Following this process, I analyze Twitter and WhatsApp datasets with following classifiers: Polynomial Naïve Bayes, Logistic Regression, Decision Trees, and Support Vector Machine 

Here is accuracy: 

Logistic regression = 99.88%, Polynomial Naïve Bayes = 99.48%, SVM = 99.76% and DT = 99.2% 

For evaluation, I check also precision, recall, f1, and confusion matrix. I found best model is logistic regression, and then I extract important features and check the confusion matrix.

Confusion matrix shows that the error in prediction in very low, which shows tokenization, normalization and modeling, have remarkable performance. 
