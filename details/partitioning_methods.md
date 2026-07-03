# Partitioning Methods (Centroid-Based)

Centroid-based partitioning algorithms recursively partition the dataset into $K$ distinct groups. A notable advancement is $K$-Means++, which optimizes the initial centroid placement to prevent suboptimal local minima.

## Algorithmic Workflow
```mermaid
graph TD
    A[Start] --> B[Choose first centroid uniformly at random]
    B --> C[Calculate distance D x to nearest existing centroid]
    C --> D[Choose next centroid with probability proportional to D x squared]
    D --> E{K centroids selected?}
    E -- No --> C
    E -- Yes --> F[Run standard K-Means optimization]
```
