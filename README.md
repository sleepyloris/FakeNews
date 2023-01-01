# Semantic Fake News Classifier


 The project was a fake news classifier which word vectors to measure semantic similarity of sentences to a corpus of fake news data which I had pre processed ( ... ). The semantic similarity approach used a novel idea of comparing subject, verb, and object phrases with eachother.   


Previous research has shown the use of semantic analysis to be useful in conjunction with syntactic analysis to detect fake news. In this project semantic analysis was used as a standalone parameter in an unsupervised learning classifier model of fake news using word embedding on the University of Victoria’s “IOST Fake News Dataset” corpus (Ahmed et al., 2017). The semantic classification was done through comparison of sentences of subjects, objects and verbs. The intuition behind this algorithm is that sentences that share semantically similar subjects, objects, and verbs, will ultimately tend to be more similar than sentences which do not. This method avoids many issues in word similarity between different word classes, whilst still conserving part of the semantically relevant information found in word order (subject/verb/object), which a method like bag-of-words would not conserve. 
