# DM-Reading-Materials
Data Mining Must to Read Materials

In this repository, I'll recommend many must reading materials to you.
It may be include the whole field of data mining, I'll try my best.

So, let me tell you how to use this repo.

In the branch of data mining, I'll set them to a title, and put some reading materials information below by it as a item. If each item has :white_check_mark: before it, just say you could find it's pdf in my corresponed sub-repo. but if you could download directly, then I suggest that you would click the item to download it.

Finally, if you have any suggestions then please tell me for email. Thanks!

Okay, Let us beginning! Good luck!


## Overview

- [x] [Wu, Xindong, et al. "Top 10 algorithms in data mining." Knowledge and information systems 14.1 (2008): 1-37.](https://link.springer.com/article/10.1007/s10115-007-0114-2)

## Basic Theory

- [x] **(Lagrange multiplier)** [Klein, Dan. "Lagrange multipliers without permanent scarring." University of California at Berkeley, Computer Science Division (2004): 1-11.](http://www-diglib.stanford.edu/~klein/lagrange-multipliers.pdf)
  - Lagrange multiplier is common core algorithm for calculation a optimization problem within constraint conditions. If you definitly understand it, then you would fastly master many machine learning algorithms.

## Data Preprocessing

- [x] [Hernández, Mauricio A., and Salvatore J. Stolfo. "Real-world data is dirty: Data cleansing and the merge/purge problem." Data mining and knowledge discovery 2.1 (1998): 9-37.](https://link.springer.com/article/10.1023/A:1009761603038)

  - This paper propose a keys sorting algorithm to clean many repeat entities from multiple databases. such as the same real-world entities are represented differently in the data sets. It would be very useful if you have to merge/purge multiple records from different databases.

- [x] [Donders, A. Rogier T., et al. "A gentle introduction to imputation of missing values." Journal of clinical epidemiology 59.10 (2006): 1087-1091.](https://www.jclinepi.com/article/S0895-4356(06)00197-1/fulltext)

- [x] (**SMOTE**)[Chawla, Nitesh V., et al. "SMOTE: synthetic minority over-sampling technique." Journal of artificial intelligence research 16 (2002): 321-357.](https://arxiv.org/abs/1106.1813)
  - This Paper proposed a ynthetic over-sampling method whcih could construction of classifier from imbalance data sets. And it also shown performance of the combination of the over-sampling minority class and the under-sampling majority class  is better than only use under-sampling majority class. Experiments are performed using C4.5, Ripper and a Naive Bayes classifier. Furthermore, the authors summarizes many previously approach and describes their disadvantage of methods.

- [x] [Japkowicz, Nathalie, and Shaju Stephen. "The class imbalance problem: A systematic study." Intelligent data analysis 6.5 (2002): 429-449.](https://dl.acm.org/doi/10.5555/1293951.1293954)
  - This paper will let you to understand what is class imblance problem and how to tackle them by re-sampling or cost-modifying methods, then how its effective in this problem. Finally it discuss the affection in modern classifier such as Decision Tree, Support Vector Machine and Nerual Network.

- [x] [Hua, Ming, and Jian Pei. "Cleaning disguised missing data: a heuristic approach." Proceedings of the 13th ACM SIGKDD international conference on Knowledge discovery and data mining. 2007.](https://dl.acm.org/doi/10.1145/1281192.1281294)

- [x] **(PCA)** [Shlens, Jonathon. "A tutorial on principal component analysis." arXiv preprint arXiv:1404.1100 (2014).](https://arxiv.org/abs/1404.1100)
  - Principal component analysis(PCA) is a widely used but it more like a black box. This paper purpose to dispel the magic behind this black box. You may be only need to read it then you would understand all of PCA.  And this paper is suit for readers of all levels, just say it better than Google.


## Visualization

- [x] [Keim, Daniel A. "Information visualization and visual data mining." IEEE transactions on Visualization and Computer Graphics 8.1 (2002): 1-8.](https://dl.acm.org/doi/10.1109/2945.981847)
  - A very useful review of visualization techniques, it propose a classification of visualization techniques method, which is based on the data type to be visualized, the visualization technique, and the interaction and distortion technique. You could find many valueable papers in it.

- [x] [Maaten, Laurens van der, and Geoffrey Hinton. "Visualizing data using t-SNE." Journal of machine learning research 9.Nov (2008): 2579-2605.](http://www.jmlr.org/papers/v9/vandermaaten08a.html)
  - This paper purpose a better than pca method, t-Stochastic Neighbor Embedding, in visualization. It is a unsupervised learning method.

## Classification

- [x] (Decision Tree **CART**) [Breiman, Leo. Classification and regression trees. Routledge, 2017.](./classification/cart-book.pdf)
  - It is a quiet classic classification and regression trees(CART) book.

- [x] (Decision Tree) [Loh, Wei‐Yin. "Classification and regression trees." Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery 1.1 (2011): 14-23.](https://onlinelibrary.wiley.com/doi/abs/10.1002/widm.8)

- [ ] (**Naive Bayes**) [Duda, Richard O., Peter E. Hart, and David G. Stork. Pattern classification. John Wiley & Sons, 2012.](https://books.google.com.hk/books?hl=zh-CN&lr=&id=Br33IRC3PkQC&oi=fnd&pg=PR3&dq=pattern+classification&ots=2xEPNrb9Jr&sig=GoiTMKG0BDB3HsqkixyvnDHAmII&redir_esc=y#v=onepage&q=pattern%20classification&f=false)
- [x] (**Naive Bayes**)[Domingos, Pedro, and Michael Pazzani. "Beyond independence: Conditions for the optimality of the simple bayesian classi er." Proc. 13th Intl. Conf. Machine Learning. 1996.](http://www.ics.uci.edu/~pazzani/Publications/mlc96-pedro.pdf)


- [x] (Bayesk Network) [Friedman, Nir, Dan Geiger, and Moises Goldszmidt. "Bayesian network classifiers." Machine learning 29.2-3 (1997): 131-163.](https://link.springer.com/article/10.1023/A:1007465528199) 

 