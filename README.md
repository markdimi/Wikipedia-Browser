# Wikipedia-Browser

Below I plotted the Greek Wikipedia articles in a 2d dynamic representation. First I created a vector representation of the documents (mainly tf-idf) and then I applied dimensionality reduction techniques in order to reduce the vector space to two dimensions. Clustering analysis is also applied at some examples. It is interesting to see that similar documents are plotted close to each other, even though I didn't work on feature extraction from the documents very long.

### Due to a change in the plotting library bokeh all the dynamic plotts stopped working. Thankfully there is a workaround and I will fix soon. For now only the first notebook in the lists works.

## Notebooks:
Interactive notebooks aren't supported in github, so nbviewer is used instead.

### Text representation

#### TF-IDF

* Wikipedia visualization of all the articles: [nbviewer link](https://nbviewer.jupyter.org/github/markdimi/Wikipedia-Browser/blob/master/notebook/Wikipedia%20visualization.ipynb) [16.5 MB]

* Wikipedia visualization of top 100 categories: [nbviewer link](https://nbviewer.jupyter.org/github/markdimi/Wikipedia-Browser/blob/master/notebook/Wikipedia%20visualization%20of%20categories.ipynb) [24.7 MB]

* Wikipedia visualization of all articles with their top category: [nbviewer link](https://nbviewer.jupyter.org/github/markdimi/Wikipedia-Browser/blob/master/notebook/Wikipedia%20visualization%20of%20categories%20-%20All%20articles%20have%20one%20category.ipynb) [37.1 MB]

### Clustering

#### K-means

* Clustering on the above tfidf using kmeans for k = 8 clusters : [nbviewer link](https://nbviewer.jupyter.org/github/markdimi/Wikipedia-Browser/blob/master/notebook/Wiki%20Viz%20Kmeans%20K%3D8.ipynb)  [75.4 MB]

* Clustering a tf-idf reduced in 2 dimensions for k = 8 clusters- experimental: [nbviewer_link](https://nbviewer.jupyter.org/github/markdimi/Wikipedia-Browser/blob/master/notebook/Wiki%20Viz%20Kmeans%20K%3D8-Clustering%20the%20svd%20matrix.ipynb) [37.7 MB]

#### LSI Topic Modeling

* Clustering the dataset using topic modeling. K = 12 : [nbviewer link](https://nbviewer.jupyter.org/github/markdimi/Wikipedia-Browser/blob/master/notebook/Wiki%20Viz%20Topic%20Clustering%20-%20LSI.ipynb)  [37.3 MB]

#### DBSCAN (on low-d matrix)

* Clustering a 2-d dimensionality reduced matrix, using dbscan with no specific attributes. Clusters generated = 155 : [nbviewer link](https://nbviewer.jupyter.org/github/markdimi/Wikipedia-Browser/blob/master/notebook/Wiki%20Viz%20dbscan%20155%20Clusters%20on%20a%20low-dimensional%20data-set.ipynb)  [74.8 MB]
