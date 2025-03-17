---
title: "Fully-Dynamic Single-Linkage Clustering"
categories: "project"
---

We study the problem of maintaining a single-linkage dendrogram in the fully-dynamic setting. 
We assume the input is a dynamic forest $F$ (representing the minimum spanning forest of the data) which receives a sequence of edge insertions and edge deletions. 
To our knowledge no prior work has provided algorithms to update an SLD asymptotically faster than recomputing it from scratch. 
All of our update algorithms are asymptotically faster than the best known static SLD computation algorithm, which takes $O(n \log h)$ time where $h$ is the height of the dendrogram ($h \leq n-1$). 
Furthermore, our algorithms are much faster in many cases, such as when $h$ is low.
Our first set of results are an insertion-only algorithm in $O(h)$ time and a deletion-only algorithm in $O(h \log (1+n/h))$ time.
Next, we describe parallel and parallel batch-dynamic versions of these algorithms which are work efficient and which have poly-logarithmic depth. 
Finally, we show how to perform insertions near-optimally in $O(c \log(1+n/c))$ work and in poly-logarithmic depth where $c$ is the number of structural changes in the dendrogram caused by the update.