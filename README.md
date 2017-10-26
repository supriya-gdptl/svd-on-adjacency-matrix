# SVD on adjacency matrix

Matrix decomposition is well known method for finding communities in the graph. In the iPython notebook, I experimented on using [Singular Value Decomposition](https://www.cs.cmu.edu/~venkatg/teaching/CStheory-infoage/book-chapter-4.pdf) on different types graph matrices: adjacency matrix, [normalized graph Laplacian matrix](http://www2.cs.cas.cz/semincm/lectures/2010-04-13-Hall.pdf) and [normalized adjacency matrix](https://people.orie.cornell.edu/dpw/orie6334/lecture7.pdf).

The iPython notebook contains study of how the choice of graph matrix affects on learning good node representations which are helpful in finding communities. I used the [complete bipartite graph](http://mathworld.wolfram.com/CompleteBipartiteGraph.html) with 3 nodes in one group and 4 nodes in other group of partition for the analysis.

The results show that <b>normalized graph Laplacian</b> is better at capturing the node features from the graph.
