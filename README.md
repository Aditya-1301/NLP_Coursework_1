# This repository contains my solutions to the first coursework for the course ECS763 Natural Language Processing

This assignment is marked out of 100 and counts for 40% towards your final grade for the module.

**Note**: This is an individual coursework. You must attempt the questions yourself and provide strong evidence for understanding your method in both your notebooks and your report.

**Objective**: In this coursework, you will implement a Support Vector Machine classifier (or SVM) that classifies tweets according to their sentiment, i.e. positive or negative. You will derive features from the text of the tweets to build and train the classifier on part of the dataset. You will then test the accuracy of your classifier on an unseen portion of the dataset. Much of the background for this part is in Lecture 2 and Lab 2 on Text Classification, though you should use all of your knowledge across the module.

**How to submit**: Follow the below instructions, and submit well documented code as one or more IPython files (.ipynb) building on the template file “NLP_Assignment_1.ipynb” as your starting point (Python 3.7+). You must also submit a 2-page report where you describe how you achieved each question briefly, with the relevant observations asked for below. You have the data in the file ‘sentimentdataset.tsv’. Ensure your code runs from top to bottom without errors before submission. If you do use more than one IPython file, it must be clear which file corresponds to which questions. The template file contains some functions to load in the dataset, but there are some missing parts that you are going to fill in as per the questions below.

## Question 1 (10 marks)
Simple data input and pre-processing. Start by implementing the parse_data_line() and the pre_process() functions. Given a line of a tab-separated text file, parse_data_line() should return a tuple containing the label and text. The simple pre_process() function should turn a text (a string) into a list of tokens (words).
