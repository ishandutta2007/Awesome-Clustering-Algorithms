# Density-Based Methods (Spatial Connectivity)

Density-based clustering discovers clusters based on density criteria (minimum density and connection distance), ignoring spatial shapes and treating sparse outliers as noise.

## Core Topology
```mermaid
graph TD
    A[Density Connectivity] --> B[Direct Density Reachable]
    A --> C[Density Reachable]
    A --> D[Density Connected]
```
