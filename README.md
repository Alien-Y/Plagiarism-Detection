# Plagiarism-Detection
Detecting plagiarism using Feature Engineering, NLP and Machine Learning.

## Project Overview
In this project, we will build a plagiarism detector that examines a text file and performs binary classification; labeling that file as either plagiarized or not, depending on how similar that text file is to a provided source text. Detecting plagiarism is an active area of research; the task is non-trivial and the differences between paraphrased answers and original work are often not so obvious.

This project will be broken down into three main notebooks:

### Notebook 1: Data Exploration

Load in the corpus of plagiarism text data.  
Explore the existing data features and the data distribution.  
This first notebook is not required in your final project submission.  


### Notebook 2: Plagiarism Feature Engineering

Clean and pre-process the text data.  
Define features for comparing the similarity of an answer text and a source text, and extract similarity features.  
Select "good" features, by analyzing the correlations between different features.  
Create train/test .csv files that hold the relevant features and class labels for train/test data points.  


### Notebook 3: Final Model

Upload your train/test feature data.  
Define a binary classification model and a training script.  
Train the model.  
Evaluate the classifier.  


### Note:  
In the notebook 4, you can provide an original text and an custom text and see if the custom text is plagiarized or not.