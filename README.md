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

# Why not just 

# Installation
Genism is an open source tool and can be directly forked from the:
https://github.com/RaRe-Technologies/gensim
Please note that:
1) You must have Python environment configured
2) You must Numpy and Scipy packages installed.
3) This tutotirla assumes that you are obtaining stopwords from NLTK library. 

Please install the latest version of genism by running the following command in your terminal
pip install --upgrade genism


# Data Preprocessing

