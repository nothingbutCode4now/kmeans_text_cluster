#Text based clustering of top 100 films.
In this project, i attempted using K means to cluster text documents, in specific, Top 100 films as per imdb, and identify their core structures or terms after clusters are formed.

Data is is obtained from imdb and wiki.

AFter tokenization and stemming, TFIDF scores are assigned to words and the data frame is supplied as feed input to kmeans. ( using elbow method, i found that 5 or 6 is optimal k).

The top terms in each cluster are then procured using cluster_centroids_ and argsort() functions.
