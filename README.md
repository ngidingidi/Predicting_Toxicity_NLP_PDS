# Predicting_Toxicity_NLP_PDS
Natural Language Processing Toxic Comments - Portland Data Science 

# Goal
Use Natural Language Processing to predict toxicity score of comments collected from Wikipedia

# Background
The original data for this project came from the Wikipedia Detox project in which comments from Wikipedia talk pages were reviewed by 10 reviewers and given a score of 2, 1, 0, -1, -2, with 2 and -2 being the score for comments that were considered most positive and most toxic, respectively. 

# Data
The data comes in two files. One file consists of unanimous toxicity scores in which all reviewers gave the same score and nonunamious data in which each reviewer gave a different score. Here I am using the unanimous data. Here is a link to the original data: http://dive-into.info/

# Analysis
I used Jupyter Notebook to perform the analysis. I imported the files, cleaned up the data, performed visualization to find interesting trends, and used Scikit-learn to evaluate the accuracy of a few classifiers to predict the toxicity score of the comments
