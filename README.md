# project-plagiarism-detection

This the project "Plagiarism Detection" developed to the Udacity Machine Learning Engineer Nanodegree.

## Table Of Contents

**Notebook 1: Data Exploration**
* Load in the corpus of plagiarism text data.
* Explore the existing data features and the data distribution.
* This first notebook is **not** required in your final project submission.

**Notebook 2: Feature Engineering**

* Clean and pre-process the text data.
* Define features for comparing the similarity of an answer text and a source text, and extract similarity features.
* Select "good" features, by analyzing the correlations between different features.
* Create train/test `.csv` files that hold the relevant features and class labels for train/test data points.

**Notebook 3: Train and Deploy Your Model in SageMaker**

* Upload your train/test feature data to S3.
* Define a binary classification model and a training script.
* Train your model and deploy it using SageMaker.
* Evaluate your deployed classifier.

**source_pytorch/**
* model.py - code to create the model
* train.py - code to train the model
* predict.py -code to use the model to perform predictions

## Disclaimer

As you may notice from the SageMaker Project.ipynb file, most of the code was provided by Udacity in order to make this project.
