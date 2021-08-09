# Text-Classification

## Introduction
The project aims to study and implement the Multinomial Naive Bayes algorithm from scratch and compare it with the inbuilt library algorithm.

## Description of Dataset
The 20 Newsgroup dataset (can be downloaded from: http://archive.ics.uci.edu/ml/machine-learning-databases/20newsgroups-mld/) consists around 20000 news articles divided in the following 20 categories:

* alt.atheism
* comp.graphics
* comp.os.ms-windows.misc
* comp.sys.ibm.pc.hardware
* comp.sys.mac.hardware
* comp.windows.x
* misc.forsale
* rec.autos
* rec.motorcycles
* rec.sport.baseball
* rec.sport.hockey
* sci.crypt
* sci.electronics
* sci.med
* sci.space
* soc.religion.christian
* talk.politics.guns
* talk.politics.mideast
* talk.politics.misc
* talk.religion.misc

For example, following is an article belonging to sci.electronics class:

![alt text](https://github.com/tushargoyal9990/Text-Classification-Project/blob/main/Images/Sample%20Article.PNG)

70% of the data i.e. 12000 articles are used for training purpose and 30% data i.e. 6000 articles are used for testing purpose.


## Methodology

* Clean the text by removing stop words and numbers.
* Build the vocabulary from training data.
* Select the top 10000 frequent words to be used as features.
* Transform the dataset into the standard format of X:Y where X is feature vector and Y is class.
* Implement the Multinomial Naive Bayes algorithm from scratch.
* Apply the scratch implementation of Multinomial Naive Bayes
* Apply inbuilt Multinomial Naive Bayes from sklearn.

## Results
The Classification Report of the implementation of the algorithm from scratch:

![alt text](https://github.com/tushargoyal9990/Text-Classification-Project/blob/main/Images/Scratch%20Implementation%20Report.PNG)

The Classification Report of the inbuilt implementation of the algorithm:

![alt text](https://github.com/tushargoyal9990/Text-Classification-Project/blob/main/Images/Inbuilt%20Implementation%20Report.PNG)

## Conclusion
The scratch implementation is on par with the inbuilt library algorithm. The accuracy of classification can be improved by using advanced NLP algorithms.
