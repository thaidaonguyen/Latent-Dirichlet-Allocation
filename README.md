# Latent Dirichlet Allocation

Latent Dirichlet Allocation (LDA) using Gensim library

This repository is my hand-on exploration on how to implement LDA.  
It consists of a compilation and modification of various resources found the web.  
The work status is in progress; therefore, the codes are not optimized and will
be improved and updated as time allows.  

LDA is a machine learning algorithm for natural language
processing. It is a method used for small dataset/vocabulary size as 
the LDA is a count-based algorithm that infer topics based on the words distribution.

Edwin Chen's blog has a clear explanation and include some good use cases:
http://blog.echen.me/2011/08/22/introduction-to-latent-dirichlet-allocation/

Dataset:  
I am using the BBC raw text dataset available at http://mlg.ucd.ie/datasets/bbc.html.
Here is its description:
*  It consists of 2225 documents from the BBC news website corresponding to stories in five topical areas from 2004-2005.
*  Class Labels: 5 (business, entertainment, politics, sport, tech)


My Next Steps:  
1.  Could test with bigger data set, and use Apache Spark distributed env't.
2.  Could explore some deep learning models for natural language processing.




