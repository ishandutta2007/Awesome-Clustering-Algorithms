# Variance-Covariance Regularization (VICReg Blocks)

VICReg enforces representation learning variance, covariance, and invariance constraints directly inside the self-supervised latent space to prevent collapse.

## Architecture
```mermaid
graph LR
    X1[Branch A] --> EncA[Encoder] --> Y1[Representation] --> ProjA[Projector] --> Z1[Embedding]
    X2[Branch B] --> EncB[Encoder] --> Y2[Representation] --> ProjB[Projector] --> Z2[Embedding]
    Z1 --> Loss[VICReg Loss: Variance, Covariance, Invariance]
    Z2 --> Loss
```
