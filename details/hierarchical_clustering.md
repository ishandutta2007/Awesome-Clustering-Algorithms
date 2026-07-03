# Hierarchical Clustering (Linkage Trees)

Hierarchical clustering constructs a tree of clusters called a dendrogram. It can be built bottom-up (agglomerative) or top-down (divisive).

## Dendrogram Merge Process
```mermaid
graph TD
    A[Data Point A] --> AB[Cluster AB]
    B[Data Point B] --> AB
    C[Data Point C] --> ABC[Cluster ABC]
    AB --> ABC
    D[Data Point D] --> ABCD[Root Cluster ABCD]
    ABC --> ABCD
```
