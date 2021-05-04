# Technical-Tutorial
Hello! This Technical Tutorial will cover how to prepare the data for topic modeling (LDA) using Genism python library.
In fact, this tutorial focuses on preparing the "user review text" dataset for different kinds of analysis.

# Why do we care about user reviews?
User reviews contain invaluable contextual information that could be used for a variety of analysis such as sentiment analysis and network analysis. 
Even a simple bigram count network could reveal important user behaviors on a specific platform (e.g., Turkopticon in this example).

# Why Genism?
Genism is a python library that is designed for topic-modeling. 
Various machine learning software packages (and algorithms) take an extensive amount of time to converge when given a large dataset. Genism is optimized to perform well on large text collections because it uses data streaming (i.e., significantly faster than the machine learning algorithms that depend on in-memory processing).
Plus, it is widely used and is compatible with other popular libraries such as NLTK.

Note that the Text data is very large! Espeically if you are breaking down sentences in to separate tokens. 

# Installation
Genism is an open source tool and can be directly forked from the:
https://github.com/RaRe-Technologies/gensim
Please note that:
1) You must have Python environment configured
2) You must Numpy and Scipy packages installed.
3) This tutotirla assumes that you are obtaining stopwords from NLTK library. 

Please install the latest version of genism by running the following command in your terminal
pip install --upgrade genism


# Data Preprocessing and Execution 
There are other excellent tutorials that shows all the steps and code to preprocess and perform LDA topic modeling:
https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/

This tutorial will mainly focus on demonstrating the use case and application.

IMPORTANT: NOTE THAT THE PREPROCESSING TAKES THE LONGEST

# Available dataset
Use the export_1000_samp.csv data from the below website to test to proceed through the Data Preprocessing and Execution step:
https://github.com/dpstyner/Technical-Tutorial

# Use case
By step 9, you should be able to construct bigrams and trigrams.
One way to represent bigram and word relations are to create a simple bigram network (See the example below).

![image](https://user-images.githubusercontent.com/48960071/117061012-850afa00-acd6-11eb-8a7d-9f3409e030b7.png)

The above image was created using a full dataset with more than 400,000 records with R Statistical software using igraph package. 

As you can see, this is quiet promising :) It looks like the user reviews are converging into a fewer set of topics!
Proceed through stop 10, step 11 to create dictionary and corpus. 

Then, see how far you can get! Please leave any commment or contact me @dpstyner on Github for any questions.

