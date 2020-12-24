# Plagiarism Detection Using Amazon SageMaker

This is the second deployment project which is part of the MLE Nanodegree.Detecting plagiarism is an active area of research; 
the task is non-trivial and the differences between paraphrased answers and original
work are often not so obvious. In this project, a plagiarism detector is developed that examines a text file and performs
binary classification; labeling that file as either plagiarized or not, depending on how similar that text file is to a provided source text.

This project is broken down into three main notebooks:

## Notebook 1: Data Exploration
1. Load in the corpus of plagiarism text data.
2. Explore the existing data features and the data distribution.

## Notebook 2: Feature Engineering
1. Clean and pre-process the text data.
2. Define features for comparing the similarity of an answer text and a source text, and extract similarity features.
3. Select "good" features, by analyzing the correlations between different features.
4. Create train/test .csv files that hold the relevant features and class labels for train/test data points.

## Notebook 3: Train and Deploy Your Model in SageMaker
1. Upload train/test feature data to S3.
2. Define a binary classification model and a training script.
3. Train the model and deploy it using SageMaker.
4. Evaluate deployed classifier.

## Prerequisites
1. AWS Account
2. Experience with model development on AWS SageMaker
4. Familiarity AWS S3
  
## Setup instructions
```
cd SageMaker
git clone 
exit
```
