# Manifold Learning Alignment Layers

Manifold learning methods like t-SNE and UMAP reduce dimensionality by mapping high-dimensional spaces to lower-dimensional manifolds while preserving local or global topological relationships.

## Dimensionality Reduction Pipeline
```mermaid
graph LR
    High[1536-D Vector] --> Graph[Construct High-Dim Graph]
    Graph --> Optimize[Minimize Divergence / Cross-Entropy]
    Optimize --> Low[2-D or 3-D Latent Coordinates]
```
