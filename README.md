# Clustering_News_articles_on-facebook
This repository contains project on clustering of news articles and headlines that are being shared on Facebook. 

**Data distribution** among topics-
![pic1](pic1.png)

Clustered news articles based on three vectorisation techniques for 2 clustering algorithms
To find the optimum number of clusters, **Elbow curve** method has been employed.
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
![pic1](pic1.png)

**TFIDF Agglomerative**
![pic1](pic1.png)

**Doc2vec KMEANS**
![pic1](pic1.png)

**Doc2vec Agglomerative**
![pic1](pic1.png)

**Word2vec KMEANS**
![pic1](pic1.png)

**Word2vec Agglomerative**
![pic1](pic1.png)

Extra Clustering with kmeans cluster tfidf technique and MDS dimensionality reduction.
![pic1](pic1.png)

Below are the stats of clusters

![pic1](pic1.png)

Observations:

With 6 type of combinations- using TF-IDF,Word2vec and Doc2vec, there results are quite different.

Doc2vVec with neither K-Means nor Agglomerative clustering algorithms performed well. They both failed to cluster topics.

TF-IDF comparitevely performed well than Doc2vec but failed to cluster topics in 1-2 categories with both K-means and agglomerative.

Word2Vec performed the best compared to both TF-IDF and Doc2Vec, Compared to K-means Agglomerative performed well and clustered topics appropriately with the sample.

Word2Vec with K-means performed very Well.




