# Social Network Community Detection
This project aims to detect communities within a social network using various community detection algorithms. The implemented algorithms include the Girvan-Newman algorithm, Fast Greedy algorithm, Modularity Maximization method, and Spinglass method.

## Introduction
The goal of this project is to analyze the community structure within a social network and identify groups of individuals with similar connections, interests, or behaviors. By applying community detection algorithms, we aim to uncover the underlying community structure and gain insights into the network dynamics.

## Algorithms Implemented

### The Clique Percolation Method (CPM)

This network clustering algorithm that identifies clusters based on the formation of k-cliques, which are complete subgraphs of size k. In the CPM, nodes that share k-1 common neighbors are considered to be part of the same k-clique. The algorithm proceeds by first finding all k-cliques in the network and then constructing a graph where each k-clique is represented as a node. Edges are added between nodes that share k-1 common nodes, forming a cluster. The resulting clusters can overlap and are referred to as "k-plexes."

### Girvan-Newman Algorithm

This algorithm identifies communities by iteratively removing edges with high betweenness centrality, which indicates their importance in connecting different communities.

### Fast Greedy Algorithm

This algorithm merges or splits communities based on their modularity gain, aiming to maximize the overall modularity of the network.
Modularity Maximization Method: This method optimizes the modularity of the network by iteratively merging communities with a higher density of internal edges.

### Modularity Maximization Method

This method optimizes the modularity of the network by iteratively merging communities with a higher density of internal edges.

### Spinglass Method
This method treats community detection as an optimization problem and seeks to minimize the energy of a spin glass model, where spins represent node assignments.
