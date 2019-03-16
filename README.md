# TopicModelingEnronEmails
This is an exploration of Topic Modeling techniques, specifically Latent Dirichlet Allocation and Non-negative Matrix Factorization using the Enron Email Dataset

The Enron Dataset was downloaded from https://archive.ics.uci.edu/ml/datasets/bag+of+words.

Inpsiration for the code and approach for LDA and NMF was found in this article: https://medium.com/mlreview/topic-modeling-with-scikit-learn-e80d33668730.

A very similar approach is shown in the Scikit Learn tutorial: https://scikit-learn.org/stable/auto_examples/applications/plot_topics_extraction_with_nmf_lda.html.

I was very intrigued by the topics that were found by the algorithms. For instance, the following topic, found by LDA, clearly shows that University of Texas at Austin (Longhorns) football games were a recurring topic:

#### Topic 9: 
#### game play free click season longhorn team yard offer texas player save start updated point gift football visit big special


Another topic points to dealings with or ramifications of the California electricity crisis of of 2000 and 2001. Enron's actions were a major factor for this crisis. See https://en.wikipedia.org/wiki/California_electricity_crisis for details. The topic refers to the Governor of Califonia at the time, Governor Davis; Pacific Gas and Electric Company (PG&E); Southern California Edison; and the Federal Energy Regulatory Commission (FERC) all of whom were stakeholders affected by the crisis.

#### Topic 7: 
#### power california energy electricity utility utilities cost davis market ferc states edison pge governor iso generator plant prices plan price
