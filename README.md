# Semantic Fake News Classifier

Previous research has shown the use of semantic analysis to be useful in conjunction with syntactic analysis to detect fake news. In this project semantic analysis was used as a standalone parameter in an unsupervised learning classifier model of fake news using word embedding on the University of Victoria’s “IOST Fake News Dataset” corpus (Ahmed et al., 2017). The copus was prepocessing data through the use of removing stop words, lemmatizing, and summarizing articles in the corpus.  

The semantic classification was done through comparison of sentences of subjects, objects and verbs. The intuition behind this algorithm is that sentences that share semantically similar subjects, objects, and verbs, will ultimately tend to be more similar than sentences which do not. This method avoids many issues in word similarity between different word classes, whilst still conserving part of the semantically relevant information found in word order (subject/verb/object), which a method like bag-of-words would not conserve. 


# Links

[Link to Full Report](https://docs.google.com/document/d/1FFKzBQzCxs2Kj40k0_0vSuWWDTUkiqa3soblt5xw13I/edit)

[Uvic's IOST Fake News Dataset](https://www.uvic.ca/ecs/ece/isot/datasets/fake-news/index.php)

