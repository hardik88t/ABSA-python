# ABSA-python
aspect-based sentiment analysis using syntactic parsing in python


## Aspect-Based Sentiment Analysis with Syntactic Parsing

This repository contains code for building an aspect-based sentiment analysis (ABSA) system based on syntactic parsing. The ABSA system is designed to predict the sentiment polarity (positive, negative, or neutral) of a given aspect term in a sentence.

The code in this repository is based on the following steps:

1. Load the XML dataset of sentences, aspect terms, and polarities.
2. Parse the sentences using dependency parsing.
3. Define rules for predicting the sentiment polarity of an aspect term based on its syntactic relationships with other words in the sentence.
4. Evaluate the precision and recall of the rules on the dataset.

The repository also includes a report that summarizes the results of the evaluation.

**To use the code in this repository, you will need the following:**

* Python 3
* The spaCy natural language processing library

**Instructions for running the code:**

1. Clone the repository to your local machine.
2. do `pip install requirements.txt`
3. Run the `absa.ipnyb` script/ open in colab

The output of the script will be a report that summarizes the results of the evaluation.

**This repository is intended for researchers and developers who are interested in learning more about aspect-based sentiment analysis.**

**The code in this repository is released under the MIT License.**
