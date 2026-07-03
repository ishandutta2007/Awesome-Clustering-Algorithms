# Enterprise Cyber-Security & Fraud Network Anomaly Tracking

Clustering high-frequency network streams groups standard transaction profiles, allowing real-time identification of malicious intrusion anomalies outside dense clusters.

## Detection Pipeline
```mermaid
graph TD
    Logs[Network Logs] --> Embed[Vectorize Logs]
    Embed --> Cluster[Clustering Pipeline]
    Cluster --> Check{Fits Standard Cluster?}
    Check -- Yes --> Normal[Log Normal Behavior]
    Check -- No --> Alert[Flag Fraud Alert / Anomaly]
```
