# PageRank
An implementation of the PageRank algorithm developed by Google founders Larry Page and Sergey Brin. This implementation was written to optimize runtime on large graphs through use of sparse matrices.The PageRank algirithm is an interative approach to finding the dominant eigenvalue of a column stochastic matrix and ranking graph nodes (webpages) based on the eigenvector corresponding to the calculated dominant eigenvalue.

The application was written in a Jupyter Notebook with PYthon 3.7. THe code can be seen in the PageRank.ipynb file and some test graphs are given. The webGoogle.npz is a large file with nearly a million elements in the graph and the code has been optimized to run the pagerank algorithm on this file.
