# Industrial Bio-Informatics & Genomic Sequencing Discoveries

Unsupervised hierarchical clustering organizes genetic sequences by evolutionary similarities, assisting in tracing viral mutations and target-specific de novo drug discovery.

## Workflow
```mermaid
graph TD
    DNA[DNA / RNA Sequences] --> Align[Sequence Alignment Matrix]
    Align --> Tree[Hierarchical Tree Linkage]
    Tree --> Clade[Identify Mutation Clades / Taxons]
```
