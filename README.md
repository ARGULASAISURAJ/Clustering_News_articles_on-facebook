# Clustering_News_articles_on-facebook

This repository contains project on clustering of news articles and headlines that are being shared on Facebook. 

**Data distribution** among topics-

![pic1](https://github.com/ARGULASAISURAJ/Clustering_News_articles_on-facebook/blob/main/pic1.PNG)

Clustered news articles based on three vectorisation techniques for 2 clustering algorithms

To find the optimum number of clusters, **Elbow curve** method has been employed.

![pic2](https://github.com/ARGULASAISURAJ/Clustering_News_articles_on-facebook/blob/main/pic2.PNG)

For **Dimensionality reduction** we used **T-SNE**

For converting word2vec to document vector a new method **MIN-MAX word vector** has been employed.

**Vectorisation**
1. TF-IDF
2. WORD2VEC
3. DOC2VEC

**Clustering Algorithm**
1.K-means
2. Agglomerative

Below are the results of clusters

**TFIDF KMEANS**
![pic3](https://github.com/ARGULASAISURAJ/Clustering_News_articles_on-facebook/blob/main/pic3.PNG)

**TFIDF Agglomerative**
![pic4](https://github.com/ARGULASAISURAJ/Clustering_News_articles_on-facebook/blob/main/pic4.PNG)

**Doc2vec KMEANS**
![pic5](https://github.com/ARGULASAISURAJ/Clustering_News_articles_on-facebook/blob/main/pic5.PNG)

**Doc2vec Agglomerative**
![pic6](https://github.com/ARGULASAISURAJ/Clustering_News_articles_on-facebook/blob/main/pic6.PNG)

**Word2vec KMEANS**
![pic7](https://github.com/ARGULASAISURAJ/Clustering_News_articles_on-facebook/blob/main/pic7.PNG)

**Word2vec Agglomerative**
![pic8](https://github.com/ARGULASAISURAJ/Clustering_News_articles_on-facebook/blob/main/pic8.PNG)

Extra Clustering with kmeans cluster tfidf technique and MDS dimensionality reduction.
![pic9](https://github.com/ARGULASAISURAJ/Clustering_News_articles_on-facebook/blob/main/pic9.PNG)

Below are the stats of clusters

![pic10](https://github.com/ARGULASAISURAJ/Clustering_News_articles_on-facebook/blob/main/pic10.PNG)

Observations:

With 6 type of combinations- using TF-IDF,Word2vec and Doc2vec, there results are quite different.

Doc2vVec with neither K-Means nor Agglomerative clustering algorithms performed well. They both failed to cluster topics.

TF-IDF comparitevely performed well than Doc2vec but failed to cluster topics in 1-2 categories with both K-means and agglomerative.

Word2Vec performed the best compared to both TF-IDF and Doc2Vec, Compared to K-means Agglomerative performed well and clustered topics appropriately with the sample.

Word2Vec with K-means performed very Well.




