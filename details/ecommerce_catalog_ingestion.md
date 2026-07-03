# Open-Vocabulary E-Commerce Product Catalog Ingestion

CLIP image-text representations mapped to shared vector spaces allow dynamic semantic sorting of unstructured merchant products into e-commerce hierarchies.

## Pipeline
```mermaid
graph LR
    Prod[Product Image & Text] --> CLIP[CLIP Encoder]
    CLIP --> Embedding[Shared Latent Vector]
    Embedding --> Map[Manifold Clustering / Classification]
    Map --> Cat[Catalog Category Taxonomy]
```
