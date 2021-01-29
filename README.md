# Edge-ML GloVe NLP

This high-speed, low-footprint **NLP** (Natural Language Processing) **EDGE-ML** (Edge Machine Learning) JavaScript library can be used to enhance and derive more info from 'TensorFlow.js' (TensorFlow JavaScript) classification predictions. This is accomplished by applying GloVe-based NLP (Natural Language Processing) on the classification labels. The most frequently associated words of the top labels are gathered, matched, ranked and sorted. This is essentially an **ML charades expert** that deduces what the unidentified object is by using the top labels as word clues.

**GloVe** (Global Vectors for Word Representation, https://nlp.stanford.edu/projects/glove/) is an unsupervised learning NLP algorithm for obtaining "word embedding" vector representations for words. Training is performed on aggregated global word-word co-occurrence statistics from a corpus, and the resulting representations showcase interesting linear substructures of the word vector space. In other words, GloVe observes that ratios of word-word co-occurrence probabilities have the potential for encoding some form of meaning. 

The data in this ML-Edge library is pre-computed using the 60,000 most frequently used pre-trained word vectors from "glove.6B.300d.txt", which is generated from Wikipedia 2014 wikis and English Gigaword 5th Edition newswire text from 1995 to 2010. The original consists of 6 billion tokens, has 400,000 uncased vocabulary, 300-dimension vectors and is 1 GB in size. Loading and such running massive sized models into a client-based web application would cause performance issues. TensorFlow suggests using a model that is of 30 MB in size or less in the browser. The NLP data in this ML-Edge library is customizable from 4-17 MB, depending on word-depth requirement from 10-50 of the most frequently used words of each vocabulary.


Edge-ML GloVe NLP with Tensorflow.js:  
[![](https://raw.githubusercontent.com/teavuihuang/edge-ml-glove-nlp/main/examples/edgeglove.png)](https://raw.githubusercontent.com/teavuihuang/edge-ml-glove-nlp/main/examples/edgeglove.png)
