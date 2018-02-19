# Predicting_Toxicity_NLP_PDS
Natural Language Processing of Toxic Comments - Portland Data Science Workshop

# Goal
Use Natural Language Processing to predict the toxicity score of comments collected from Wikipedia

# Warning
Please be warned that some of the comments use strong sexual language and racial undertones

# Background
The original data for this project came from the Wikipedia Detox project in which comments from Wikipedia talk pages were reviewed by 10 reviewers and given a score of 2, 1, 0, -1, -2, with 2 and -2 being the score for comments that were considered most positive and most toxic, respectively. A score of 0 indicates that the comments were deemed neutral

# Data
The data comes in two files. One file consists of unanimous toxicity scores in which all reviewers gave the same score and nonunamious data in which each reviewer gave a different score. Here I am using the unanimous data. Here is a link to the original data: http://dive-into.info/

# Analysis
I used Python in Jupyter Notebook to perform the analysis. I imported the files, cleaned up the data, performed data visualization to find interesting trends, and used Scikit-learn to evaluate the accuracy of a few classifiers to predict the toxicity score of the comments

# Conclusion
Applying a Random Forest and Multinomial Naive Bayes Classifier to the dataset gives an accuracy score of around 88% for both. Although the accuracy score if high, the 2 classifiers might be biased towards predicting neutral comments accurately since the data contains more neutral comments than toxic. It would be interesting to apply both classifiers to the non-unamious dataset and evaluating their accuracy
