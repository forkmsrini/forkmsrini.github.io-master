---
layout: post
title: Supervised Vs. Unsupervised Learning. Explained! [Tech]
comments: True
---

Local Author : Foreign Author :: Supervised Learning : Unsupervised Learning 

I will attempt to explain how I first perceived the concept and difference between supervised and unsupervised learning initially. 

###Appendix

Training Data: a set of all data points used for learning.

Testing Data: a set of data points used only for testing. This dataset set is not used for learning. Shall provide unbiased evaluation of the learning technique.

###Nomenclature:

Local Author: Books written by members of the local university fraternity. The content is developed after much work, to easy the burden of going through large volumes of text.

Prescribed/foreign author: Books available internationally. Largely generalised on the subject.

###Pointers:

Training Data --> Text books, notes, and other resources. (You may be familiar with this material)

Training Data --> Exam question paper. (You have not seen this paper before.)

####One Liner
Now, supervised learning is studying for an exam from locally authored books. Unsupervised learning is preparing for that exam from the list of prescribed author's books.

###Overview
 Supervised learning is a method where the required input is supplied. Labels (aka class names) are available for the classification. This learning method is fast and accurate. It is important to choose the right training set. Must be able to generalise. What is generalisation? It is ability to generate valid output for situations that haven't been encountered during the training process. Overfitting must be avoided.

Unsupervised learning systems are not provided any training data. The input data is clustered on the basis of few statistical (intrinstic) properties. The data points may be categorised into many groups. The underlying natural structure of the data is learned. This is the strength and weakness of this approach simultaneously unlike a classification task. It becomes hard to set a standard for evaluation of the clustering techniques. 

###Explained!

Supervised learning is like preparing for an exam from a local author book. The content is exam-specific, targeted and most importantly has clear structure. 'Topics' are labelled in the 'lessons' which are in turn classified into 'units'. The is no uncertainty in what to study in which unit. The reader has the comfort of pre-defined structure. The only task carried out is to identify the correct solution(s) to the question posed. 

Unsupervised learning is like preparing from a foreign author book. 'Units' are not structured in order, 'topics' may be approached differently and placed else where. There may exist situations where more than one book is required to compose the solution. The reader needs to apply his/her discretion to assess the relevance of the material for the upcoming quiz. Apart from the test of assessment of relevance, identifying the correct solution(s) to the question is required to be preformed.

In both cases, the quiz is the testing set, literally. The contents of the quiz is unknown while preparing. The type of content available from the two types of books, defines the method of learning. Naturally, unsupervised learning leads to more cumulative knowledge gain. Supervised learning serves the purpose of passing the course. Both are essential given the influence of many external parameters. 

<!-- Another perspective to understand the difference between the two methods is considering the grading system. If there is a specific score indicated to pass the quiz, the method used would be supervised learning. As there is a boundary between passing and failing, there shall be no uncertainty. All candidates securing (lets say) 50 points, pass and those who don't fail. Clearly there are two class of results. Classifying candidates into any one of the classes is straight forward.

In unsupervised learning, the result is candidate dependent. The result may be derived from previous aggregates or may depend on the class average. In such case, the group is divided into classes where candidates may pass the course in the later quiz, candidates who have passed the course and candidates who have unfortunately failed to collect the required credits. Candidates are grouped into clusters. -->

###Algorithms

Supervised learning: Neural Networks, Multi-Layer Perceptron, Decision Trees.

Unsupervised learning: Types of Clustering, K-means, Self Organising Maps.

It is worth mentioning that there are two more types of learning in addition to the above mentioned. They are weakly-supervised and semi-supervised learning.

<hr/>

###Alert Note
The example used here is tricky (not in the technical sense) and might not be familiar to all. The nomenclature is highly locale specific. Don't get confused by learning activity and trivialise the complex nature of human learning capabilities with machines. The content and quality of any book is not debated here. I draw references to explain the ways of preparing for a quiz from personal experiences and acknowledge that all books are a primary source of learning. 

This post is not the correct approach to understand the concepts of machine learning. This post may/may not supplement the understanding process. 

###Further Reading
[1] Vapnik, V. N.; [_The Nature of Statistical Learning Theory (2nd Ed.),_](http://www.springer.com/statistics/physical+%26+information+science/book/978-0-387-98780-4) Springer Verlag, 2000.

[2] C.E. Brodely and M.A. Friedl; [_Identifying and Eliminating Mislabeled Training Instances,_](http://jair.org/media/606/live-606-1803-jair.pdf) Journal of Artificial Intelligence Research 11, 131-167, 1999. 

[3] Jordan, Michael I.; Bishop, Christopher M.; [_Neural Networks,_](http://dspace.mit.edu/handle/1721.1/7186) 2004. 

[4] Hastie,Trevor,Robert Tibshirani, Friedman,Jerome; [_The Elements of Statistical Learning: Data mining,Inference,and Prediction,_](http://statweb.stanford.edu/~tibs/ElemStatLearn/) New York: Springer. pp. 485–586, 2009.

[5] Zoubin Ghahramani; [_Unsupervised Learning,_](http://mlg.eng.cam.ac.uk/zoubin/papers/ul.pdf) 2004.

[6] Christian Biemann (Thesis); [_Unsupervised and Knowledge-free Natural Language Processing in the Structure Discovery Paradigm,_](http://wortschatz.uni-leipzig.de/~cbiemann/pub/2007/Biemann07diss_Structure-Discovery-final.pdf) 2007.

[7] Use Google.

Forum for open source machine learning software is [here](http://www.mloss.org/software/).

<hr/>
