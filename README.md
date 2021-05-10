# Bipartite Graph Coclustering


Bipartite graph coclustering (BGC) is to cluster a bipartite graph based on finding minimum cut vertepartitions in a bipartite graph between
them. The given data is a table of connected pairs. We model it as a bipartite graph and then model it as a two dimenional matrix. It simultaneous clusters the rows and columns of the matrix based on singular vector decomposition and K-mean to output the clustering result.


## Table of content
- [Installation](#installation)
 
- [BGC flow](#BGC-flow)


## Installation

- Hadoop
- Spark


## BGC flow


- Read from a table of pairs 

- Create bipartite graph

- Create the adjacency matrix

- Bipartite graph Spectral colustering

- Create Laplacian matrix

- Do Singular value decomposition to get singular matrix

- Run k-means algorithm on the singular matrix


