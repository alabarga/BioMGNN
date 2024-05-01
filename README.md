# BioMGNN

We propose the construction of a multi-layer graph representation, which will be called BioMGNN (Biological Multiple Graph Neural Network), where each node represents an entity (e.g., gene, transcript, microRNA, patient, etc) and the edges represent relationships or interactions between them. The graph can incorporate multiple omics layers, where each layer corresponds to a specific type of biological entity. We can then apply graph convolutional operations to propagate information through the graph structure. GCNs leverage the graph topology to update the node features based on their neighborhood relationships. This enables capturing local and global patterns within the multi-omics data and allows downstream analysis such as patient classification or biormarker discovery.

![](https://private-user-images.githubusercontent.com/166339/300180580-32e2a4bb-a33c-44c8-8447-079b1b3ff9cc.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTQ1NDU0MDgsIm5iZiI6MTcxNDU0NTEwOCwicGF0aCI6Ii8xNjYzMzkvMzAwMTgwNTgwLTMyZTJhNGJiLWEzM2MtNDRjOC04NDQ3LTA3OWIxYjNmZjljYy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTAxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUwMVQwNjMxNDhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1iOTYzOTNjOWQ2NTBjYTE4YWIzZDAwMzFlYjI2ZWU0ZGNjMzQ1NGNkMmYyNWE0NTRkNzY1ZDhkYWVjZTVjMmFjJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.Vfo4Qp1n07YQENFj6nIBiOAuN9gG3MaeP4lYPuTl5V4)

## Getting started

-  Clone this repo: `git clone https://github.com/alabarga/BioMGNN/`
-  Enter the created folder: `cd BioMGNN`
-  Install requirements: `pip install -r requirements.txt`
-  Open Jupyter notebook `jupyter notebook` or VS code `code .`
-  Run [tutorial.ipynb](https://github.com/alabarga/BioMGNN/blob/main/tutorial.ipynb)
