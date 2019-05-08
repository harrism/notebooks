# RAPIDS Notebooks and Utilities

## XGBoost Notebook
| Folder    | Notebook Title         | Description                                                                                                                                                                                                                   |
|-----------|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| XGBoost   | XGBoost Demo           | This notebook shows the acceleration one can gain by using GPUs with XGBoost in RAPIDS.                                                                                                                                       |
## CuML Notebooks
 The cuML notebooks showcase how to use the machine learning algorithms implemented in cuML along with the advantages of using cuML over scikit-learn. These notebooks compare the time required and the performance of the algorithms. Below are a list of such algorithms:
 
| Folder    | Notebook Title         | Description                                                                                                                                                                                                                   |
|-----------|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| cuML      | dbscan_demo            | This notebook showcases density-based spatial clustering of applications with noise (dbscan) algorithm using the `fit` and `predict` functions                                                                              |
| cuML      | knn_demo               | This notebook showcases k-nearest neighbors (knn) algorithm using the `fit` and `kneighbors` functions                                                                                                                          |
| cuML      | Linear Regression Demo | This notebook includes code example for linear regression algorithm and it showcases the `fit` and `predict` functions.                                                                                                                                             |
| cuML      | Ridge Regression Demo  | This notebook includes code examples of ridge regression and it showcases the `fit` and `predict` functions.                                                                                                                                          |
| cuML      | Coordinate Descent     | This notebook includes code examples of lasso and elastic net models. These models are placed together so a comparison between the two can also be made in addition to their sklearn equivalent.                                                                                                                                                                |
| cuML      | pca_demo               | This notebook showcases principal component analysis (PCA) algorithm where the model can be used for prediction (using `fit_transform`) as well as converting the transformed data into the original dataset (using `inverse_transform`).                                                                                                                |
| cuML      | tsvd_demo              | This notebook showcases truncated singular value decomposition (tsvd) algorithm which like PCA performs both prediction and transformation of the converted dataset into the original data using `fit_transform` and `inverse_transform` functions respectively                                                                                                     |
| cuML      | sgd_demo               | The stochastic gradient descent algorithm is demostrated in the notebook using `fit` and `predict` functions                                                                        |
| cuML      | umap_demo              | The uniform manifold approximation & projection algorithm is compared with the original author's equivalent non-GPU \Python implementation using `fit` and `transform` functions                       |
| cuML      | umap_demo_graphed      | Demonstration of cuML uniform manifold approximation & projection algorithm's supervised approach against mortgage dataset and comparison of results against the original author's equivalent non-GPU \Python implementation. |
| cuML      | umap_demo_supervised   | Demostration of UMAP supervised training.  Uses a set of labels to perform supervised dimensionality reduction. UMAP can also be trained on datasets with incomplete labels, by using a label of "-1" for unlabeled samples. |

## CuGraph Notebooks
| Folder    | Notebook Title         | Description                                                                                                                                                                                                                   |
|-----------|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| cuGraph   | Louvain                | Demonstration of using cuGraph to identify clusters in a test graph using the Louvain algorithm                                                                                                                               |
| cuGraph   | Vertex-Similarity      | Demonstration of using cuGraph to compute vertex similarity using both the Jaccard Similarity and the Overlap Coefficient.                                                                                                    |
| cuGraph   | Weighted-Jaccard       | Demonstration of using cuGraph to compute the Weighted Jaccard Similarity metric on our training dataset.                                                                                                                     |
| cuGraph   | Renumber               | Demonstrate of using the renumbering features to assigned new vertex IDs to the test graph.  This is useful for when the data sets is  non-contiguous or not integer values                                                   |
| cuGraph   | BFS                    | Demonstration of using cuGraph to computer the Bredth First Search space from a given vertex to all other in our training graph                                                                                               |
| cuGraph   | SSSP                   | Demonstration of using cuGraph to computer the The Shortest Path from a given vertex to all other in our training graph                                                                                                       |
| cuGraph   | Spectral-Clustering    | Demonstration of using cuGraph to identify clusters in a test graph using Spectral Clustering using both the (A) Balance Cut and (B) the Modularity Maximization quality metrics                                              |
| cuGraph   | Pagerank               | Demonstration of using both NetworkX and cuGraph to compute the PageRank of each vertex in our test dataset                                                                                                                   |
| cuGraph   | Triangle Counting      | Demonstration of using both NetworkX and cuGraph  to compute the the number of Triangles in our test dataset                                                                                                                  |
You can now import Markdown table code directly using File/Paste table data... dialog.

## Tutorial with an End to End workflow

| Folder    | Notebook Title         | Description                                                                                                                                                                                                                   |
|-----------|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Tutorials | DBSCAN_demo_full       | Demonstration of how to use DBSCAN - a popular clustering algorithm - and how to use the GPU accelerated implementation of this algorithm in RAPIDS.                                                                               |

## Utils Scripts
| Folder    | Script Title         | Description                                                                                                                                                                                                                   |
|-----------|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Utils     | start-jupyter.sh       | starts a JupyterLab environment for interacting with, and running, notebooks                                                                                                                                                  |
| Utils     | stop-jupyter.sh        | identifies all process IDs associated with Jupyter and kills them                                                                                                                                                             |
| Utils     | dask-cluster.py        | launches a configured Dask cluster (a set of nodes) for use within a notebook                                                                                                                                                 |
| Utils     | dask-setup.sh          | a low-level script for constructing a set of Dask workers on a single node                                                                                                                                                    |
| Utils     | split-data-mortgage.sh | splits mortgage data files into smaller parts, and saves them for use with the mortgage notebook                                                                                                                              |

## Documentation (WIP) 
| Folder    | Document Title         | Description                                                                                                                                                                                                                   |
|-----------|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Docs      | ngc-readme             |                                                                                                                                                                                                                               |
| Docs      | dockerhub-readme       |                                                                                                                                                                                                                               |

## Additional Information
* The `cuml` folder also includes a small subset of the Mortgage Dataset used in the notebooks and the full image set from the Fashion MNIST dataset.

* `utils`: contains a set of useful scripts for interacting with RAPIDS
