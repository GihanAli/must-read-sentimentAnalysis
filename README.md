# must-read-sentimentAnalysis
List of Resources for Sentiment Analysis Starter Researcher 


## Papers:
### Sentiment Classification : 
1.  [Turney 2002 : Thumbs up or thumbs down?](http://dl.acm.org/citation.cfm?id=1073153)
  - everyone starts withthis paper, probably because it’s the oldest notable work there in sentiment classification,
  turney using two words “excellent” and “poor” and point wise mutual PMI information to do unsupervised sentiment classification 
2. [Pang, Lee 2002 : Thumbs up?: sentiment classification using machine learning techniques](http://dl.acm.org/citation.cfm?id=1118704)
cited 3K times also for the same reason above, paper in bullets : 
  - Published a movie reviews dataset that everyone uses until now 
  - used Machine learning classifiers for  3 k-folds crossvalidation
  - features were basic bag of words (unigrams and/or bigrams) word existence, word freq ( no tfidf )
  - other additional features : top unigrams, adjectives, position
  - compared results to results of features manually selected by two manual annotators 
  - Accuracy of baseline (manual annotated features ~60-70%) 
  - Accuracy of ML ~80-83%

### Sentiment Analysis in Arabic Language:

1. [El-Beltagy, Samhaa R., and Ahmed Ali. "Open issues in the sentiment analysis of arabic social media: A case study." Innovations in Information Technology (IIT), 2013 9th International Conference on. IEEE, 2013.](http://tmrg.nileu.edu.eg/resources/publications/Samhaa_OpenIssuesintheSentiment_IIT2013.pdf)
  - overview of main issues and obstacles in arabic social media sentiment analysis 
  - semi-automatic generation of ~4k entries egyptian dialect sentiment lexicon (link available in the paper) using  conjunctions 
  - Evaluation of Generated Lexicon

### Books:

1.  [Bing Liu : Sentiment Analysis and Opinion Mining ](http://www.cs.uic.edu/~liub/FBS/SentimentAnalysis-and-OpinionMining.pdf) 
Book is a thorough literature review in various issues of sentiment analysis, this could be nice to get the big picture of sentiment analysis and also to  get related work in any of the issues of sentiment analysis.


### Courses:

1. [NLP - Stanford] (https://www.coursera.org/course/nlp)



### Datasets:

### People : 

### Glossary :
[The Natural Language Processing Dictionary](www.cse.unsw.edu.au/~billw/nlpdict.html) : Glossary contains definitions of wide range of used terms in Natural language processing topics, very useful when reading papers.

### Miscellaneous:
1. [Chris. Manning : deep learning without magic part 1](http://techtalks.tv/talks/deep-learning-for-nlp-without-magic-part-1/58414/) : 
  main interesting points : 
  - Representing each word by a feature vectors built from words in context
  - Using Deep Neural networks to adapt those feature weights 
  - use those adapted feature vectors in multiple NLP classification problems
  - the old way : [AL Maas et al. : Learning Word Vectors for Sentiment Analysis](http://ai.stanford.edu/~ang/papers/acl11-WordVectorsSentimentAnalysis.pdf)


-----
### Contributing:
Feel Free to Send a [pull Request](https://help.github.com/articles/using-pull-requests/) with any updates you think it's good to add 
