# Wikipedia-Browser
Project and relevant files. Dataset used is the Greek Wikipedia corpus.

## Notebooks:
Interactive notebooks aren't supported in github, so nbviewer is used instead.

### Text representation

#### TF-IDF

* Wikipedia visualization of all the articles: [nbviewer link](https://nbviewer.jupyter.org/github/dmarkos/Wikipedia-Browser/blob/master/notebook/Wikipedia%20visualization.ipynb) [16.5 MB]

* Wikipedia visualization of top 100 categories: [nbviewer link](https://nbviewer.jupyter.org/github/dmarkos/Wikipedia-Browser/blob/master/notebook/Wikipedia%20visualization%20of%20categories.ipynb) [24.7 MB]

* Wikipedia visualization of all articles with their top category: [nbviewer link](https://nbviewer.jupyter.org/github/dmarkos/Wikipedia-Browser/blob/master/notebook/Wikipedia%20visualization%20of%20categories%20-%20All%20articles%20have%20one%20category.ipynb) [37.1 MB]

### Clustering

#### K-means

* Clustering on the above tfidf using kmeans for k = 8 clusters : [nbviewer link](https://nbviewer.jupyter.org/github/dmarkos/Wikipedia-Browser/blob/master/notebook/Wiki%20Viz%20Kmeans%20K%3D8.ipynb)  [75.4 MB]

* Clustering a tf-idf reduced in 2 dimensions for k = 8 clusters- experimental: [nbviewer_link](https://nbviewer.jupyter.org/github/dmarkos/Wikipedia-Browser/blob/master/notebook/Wiki%20Viz%20Kmeans%20K%3D8-Clustering%20the%20svd%20matrix.ipynb) [37.7 MB]

#### LSI Topic Modeling

* Clustering the dataset using topic modeling. K = 12 : [nbviewer link](https://nbviewer.jupyter.org/github/dmarkos/Wikipedia-Browser/blob/master/notebook/Wiki%20Viz%20Topic%20Clustering%20-%20LSI.ipynb)  [37.3 MB]

#### DBSCAN (on low-d matrix)

* Clustering a low-d using using dbscan with no specific options. Clusters generated = 155 : [nbviewer link](https://nbviewer.jupyter.org/github/dmarkos/Wikipedia-Browser/blob/master/notebook/Wiki%20Viz%20dbscan%20155%20Clusters%20on%20a%20low-dimensional%20data-set.ipynb)  [74.8 MB]
