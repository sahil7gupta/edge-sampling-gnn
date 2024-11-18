Repo for Course Project CIS 700 - Machine Learning with Graphs

# Edge Sampling in GNNs

Graph neural networks (GNNs) have become standard tools for learning tasks on graphs. By
iteratively aggregating information from neighborhoods, GNNs embed each node from its k-hop
neighborhood and provides a significant improvement over traditional methods in node
classification and link prediction tasks. However, most GNN models need a complete underlying
network structure, which is often unavailable in real-world settings. Frequently it is the case that
only a portion of the underlying network structure is observed, which can be considered as the
result of graph sampling [1].
We consider the observed incomplete network structure as one random sampling instance from a
complete graph, then we address the fundamental problem of GNN performance under graph
sampling. [1]
1. Can we use GNNs if only a portion of the network structure is observed?
2. Which graph sampling methods and GNN models should we choose?

Please see project report for more details.
