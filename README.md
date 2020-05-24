# DM-Reading-Materials
Data Mining Must to Read Materials | 数据挖掘必读论文

### Using description

In this repository, I am going to recommend many must reading materials to you. It may be include the whole field of data mining, I will try my best.

So, let me show you how to use this repo.

In the branch of data mining, I am going to set them to a title, and put some reading materials information below by it as a item(For each paper, I am goint to set their title as **bold** style). If each item has :ballot_box_with_check: before it, just say you could find its pdf in my corresponed sub-repo. but if you could download directly, then I suggest that you would click the item to download it. 

Then you could see that have :star: before some items, it indicate that this paper was a highly influential in its field, as well as I really recommend you could read it carefully. 

In addition, I am going to write down some thinking about this paper below some items, them just show that my perception after reading them. Hopefully, they could help you to master fastly the whole centre of papers.

Finally, if you have any suggestions then please tell me for email. Thanks!

Okay, Let us beginning! Good luck!

### 使用说明

本人在学习数据挖掘理论的时候收集了一些论文，我将其中有一些写的非常的好(有很大影响力)的文章放在这个仓库里，供大家阅读，节省文献减少的时间。我会竭尽所能地记录数据挖掘几大领域的好文章。

这个repo的使用说明如下：

我会以该文章的完整引用格式作为索引（每篇论文的题目我都会加粗显示），如果索引前面带有 :ballot_box_with_check: 则说明可以在repo对应的目录中找到该论文的pdf版，仅作学习交流用途，如果有能力的读者可以直接点击索引进行下载。

如果某些论文索引前面带有 :star: 就表明该论文我建议您仔细阅读。

此外，我还会在一些论文索引下面记录我自己的感悟，我希望这些能够帮助您快速掌握文章的中心。

最后，若您有关于此repo的任何疑惑或者想要和我一起帮助他人，请发邮件给我。感谢！

祝大家学习愉快，科研顺利！


| Content | | |
|  ----  | ----  | ---- |
|[Suvery](#survey) | [Basic Theory](#basic-theory) | [Data Preprocessing](#data-preprocessing)|
| [Visualization](#visualization) | [Classification](#classification) | [Clustering](#clustering) |
| [Frequent Pattern](#frequent-pattern) | ... | ... |


## [Survey](#content)

- [x] [**"Educational data mining: a review of the state of the art."** IEEE Transactions on Systems, Man, and Cybernetics, Part C (Applications and Reviews) 40.6 (2010): 601-618.](https://ieeexplore.ieee.org/document/5524021)
  - This paper is focus on the field of Educational data mining(EDM) which deal with different type of data in education area. Although it not the full meaning of data mining, but we could still understand the concept of data mining from it.

- [x] :star: [Wu, Xindong, et al. **"Top 10 algorithms in data mining."** Knowledge and information systems 14.1 (2008): 1-37.](https://link.springer.com/article/10.1007/s10115-007-0114-2)
  - This paper introduct 10 algorithms in data mining, they are included  association analysis, classification, clustering, statistical learning, bagging and boosting, sequential patterns, integrated mining, rough sets, link mining and graph mining, and them were pretty widely used in data mining research. So this paper would let us to understand how to do in data mining prefectly with them.

- [x] :star: [Yang, Qiang, and Xindong Wu. **"10 challenging problems in data mining research."** International Journal of Information Technology & Decision Making 5.04 (2006): 597-604.](https://www.worldscientific.com/doi/abs/10.1142/S0219622006002258)
  - This paper dicussed the hotest ten topic of data mining, such as time series mining, recognize complex knowledges and mining network stream etc. Even though issued in 2005, but it still has a great value to`` miner in today.

- [x] [Donoho, D. (2017). **50 Years of Data Science.** Journal of Computational and Graphical Statistics, 26(4), 745–766.](https://doi.org/10.1080/10618600.2017.1384734)



## [Basic Theory](#content)

- [x] (Lagrange multiplier) [Klein, Dan. **"Lagrange multipliers without permanent scarring."** University of California at Berkeley, Computer Science Division (2004): 1-11.](http://www-diglib.stanford.edu/~klein/lagrange-multipliers.pdf)
  - Lagrange multiplier is common core algorithm for calculation a optimization problem within constraint conditions. If you definitly understand it, then you would fastly master many machine learning algorithms.

- [x] [Boyd S, Boyd S P, Vandenberghe L. **Convex optimization**[M]. Cambridge university press, 2004.](https://web.stanford.edu/~boyd/cvxbook/)
  - A pretty nice book for optimization of mathematical, and it is free to download. You could get anything(ebook, extra-practice, code) on the website. Amazingly, its all of the code were written by Python, Matlab and Julia, and you also could directly download them in this repo.

## [Data Preprocessing](#content)

- [x] [Hernández, Mauricio A., and Salvatore J. Stolfo. **"Real-world data is dirty: Data cleansing and the merge/purge problem."** Data mining and knowledge discovery 2.1 (1998): 9-37.](https://link.springer.com/article/10.1023/A:1009761603038)

  - This paper propose a keys sorting algorithm to clean many repeat entities from multiple databases. such as the same real-world entities are represented differently in the data sets. It would be very useful if you have to merge/purge multiple records from different databases.

- [x] [Donders, A. Rogier T., et al. **"A gentle introduction to imputation of missing values."** Journal of clinical epidemiology 59.10 (2006): 1087-1091.](https://www.jclinepi.com/article/S0895-4356(06)00197-1/fulltext)

- [x] :star: (SMOTE)[Chawla, Nitesh V., et al. **"SMOTE: synthetic minority over-sampling technique."** Journal of artificial intelligence research 16 (2002): 321-357.](https://arxiv.org/abs/1106.1813)
  - This Paper proposed a ynthetic over-sampling method whcih could construction of classifier from imbalance data sets. And it also shown performance of the combination of the over-sampling minority class and the under-sampling majority class  is better than only use under-sampling majority class. Experiments are performed using C4.5, Ripper and a Naive Bayes classifier. Furthermore, the authors summarizes many previously approach and describes their disadvantage of methods.

- [x] :star: [Japkowicz, Nathalie, and Shaju Stephen. **"The class imbalance problem: A systematic study."** Intelligent data analysis 6.5 (2002): 429-449.](https://dl.acm.org/doi/10.5555/1293951.1293954)
  - This paper will let you to understand what is class imblance problem and how to tackle them by re-sampling or cost-modifying methods, then how its effective in this problem. Finally it discuss the affection in modern classifier such as Decision Tree, Support Vector Machine and Nerual Network.

- [x] [Hua, Ming, and Jian Pei. **"Cleaning disguised missing data: a heuristic approach."** Proceedings of the 13th ACM SIGKDD international conference on Knowledge discovery and data mining. 2007.](https://dl.acm.org/doi/10.1145/1281192.1281294)

- [x] (PCA) [Shlens, Jonathon. **"A tutorial on principal component analysis."** arXiv preprint arXiv:1404.1100 (2014).](https://arxiv.org/abs/1404.1100)
  - Principal component analysis(PCA) is a widely used but it more like a black box. This paper purpose to dispel the magic behind this black box. You may be only need to read it then you would understand all of PCA.  And this paper is suit for readers of all levels, just say it better than Google.


## [Visualization](#content)

- [x] :star: [Keim, Daniel A. **"Information visualization and visual data mining."** IEEE transactions on Visualization and Computer Graphics 8.1 (2002): 1-8.](https://dl.acm.org/doi/10.1109/2945.981847)
  - A very useful review of visualization techniques, it propose a classification of visualization techniques method, which is based on the data type to be visualized, the visualization technique, and the interaction and distortion technique. You could find many valueable papers in it.

- [x] [Maaten, Laurens van der, and Geoffrey Hinton. **"Visualizing data using t-SNE."** Journal of machine learning research 9.Nov (2008): 2579-2605.](http://www.jmlr.org/papers/v9/vandermaaten08a.html)
  - This paper purpose a better than pca method, t-Stochastic Neighbor Embedding, in visualization. It is a unsupervised learning method.

- [x] [Grinstein, G., Trutschl, M., & Cvek, U. (2001). **High-dimensional visualizations.** Data Mining Conference KDD Workshop, 1–14.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.103.528&amp;rep=rep1&amp;type=pdf)
  - This paper would show you many common data visualizations techniques, especially high-dimensions, in nowadays, and it would show you how they are work.

## [Classification](#content)

- [x] :star: (CART) [Breiman, Leo. **Classification and regression trees.** Routledge, 2017.](./classification/cart-book.pdf)
  - It is a quiet classic classification and regression trees(CART) book.

- [x] :star: [Loh, Wei‐Yin. **"Classification and regression trees."** Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery 1.1 (2011): 14-23.](https://onlinelibrary.wiley.com/doi/abs/10.1002/widm.8)
  - This paper purpose of showing the overview of all of CART(classification and regression tree) for you, those algorithms be abstracted by this paper.You would definitely get some knowledge for CART from it.

- [ ] (Naive Bayes) [Duda, Richard O., Peter E. Hart, and David G. Stork. **Pattern classification.** John Wiley & Sons, 2012.](https://books.google.com.hk/books?hl=zh-CN&lr=&id=Br33IRC3PkQC&oi=fnd&pg=PR3&dq=pattern+classification&ots=2xEPNrb9Jr&sig=GoiTMKG0BDB3HsqkixyvnDHAmII&redir_esc=y#v=onepage&q=pattern%20classification&f=false)
- [x] (Naive Bayes)[Domingos, Pedro, and Michael Pazzani. **"Beyond independence: Conditions for the optimality of the simple bayesian classifer."** Proc. 13th Intl. Conf. Machine Learning. 1996.](http://www.ics.uci.edu/~pazzani/Publications/mlc96-pedro.pdf)


- [x] (Bayesk Network) [Friedman, Nir, Dan Geiger, and Moises Goldszmidt. **"Bayesian network classifiers."** Machine learning 29.2-3 (1997): 131-163.](https://link.springer.com/article/10.1023/A:1007465528199) 

- [x] (SVM) [Burges, Christopher JC. **"A tutorial on support vector machines for pattern recognition."** Data mining and knowledge discovery 2.2 (1998): 121-167.](https://link.springer.com/article/10.1023/A:1009715923555)

- [x] (SVM) [Boser, Bernhard E., Isabelle M. Guyon, and Vladimir N. Vapnik. **"A training algorithm for optimal margin classifiers."** Proceedings of the fifth annual workshop on Computational learning theory. 1992.](https://dl.acm.org/doi/abs/10.1145/130385.130401)


# [Clustering](#content)

- [x] :star: (Review)[Jain, A. K. (2010). **Data clustering: 50 years beyond K-means**. Pattern Recognition Letters, 31(8), 651–666.](https://doi.org/10.1016/j.patrec.2009.09.011)

- [x] (The Gap Statistic)[Tibshirani, R., Walther, G., & Hastie, T. (2001). **Estimating the number of data clusters via the gap statistic.** In Journal of the Royal Statistical Society: Series B (Vol. 63, Issue Part 2, pp. 411–423).](https://doi.org/10.1111/1467-9868.00293)

- [x] [Erich Schubert, Peter J. Rousseeuw: **Faster k-Medoids Clustering: Improving the PAM, CLARA, and CLARANS Algorithms.** Similarity Search and Applications. SISAP 2019: 171-187](https://doi.org/10.1007/978-3-030-32047-8_16)


# [Frequent Pattern](#content)

- [x] :star: (Overview) [J. Han, H. Cheng, D. Xin, and X. Yan, **“Frequent pattern mining: Current status and future directions”**.](https://link.springer.com/article/10.1007/s10618-006-0059-1)

- [x] (Apriori) [Agrawal, Rakesh, and Ramakrishnan Srikant. **"Fast algorithms for mining association rules."** Proc. 20th int. conf. very large data bases, VLDB. Vol. 1215. 1994.](https://web.stanford.edu/class/cs345d-01/rl/ar-mining.pdf)

  - Apriori algorithm, really classical paper in discovery of frequent pattern.

- [x] (FP-growth) [Han, J., Pei, J., & Yin, Y. (2000). **Mining frequent patterns without candidate generation.** ACM sigmod record, 29(2), 1-12.](https://dl.acm.org/doi/abs/10.1145/335191.335372)

  - Freqent pattern growth algorithm.

- [x] (FP-Max) [Grahne, Gosta & Zhu, Jianfei. (2003). **Efficiently Using Prefix-trees in Mining Frequent Itemsets.** FIMI'03 Workshop on Frequent Itemset Mining Implementations: 2003.](https://www.researchgate.net/publication/220845998_Efficiently_Using_Prefix-trees_in_Mining_Frequent_Itemsets)
 