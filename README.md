# BioMGNN

We propose the construction of a multi-layer graph representation, which will be called BioMGNN (Biological Multiple Graph Neural Network), where each node represents an entity (e.g., gene, transcript, microRNA, patient, etc) and the edges represent relationships or interactions between them. The graph can incorporate multiple omics layers, where each layer corresponds to a specific type of biological entity. We can then apply graph convolutional operations to propagate information through the graph structure. GCNs leverage the graph topology to update the node features based on their neighborhood relationships. This enables capturing local and global patterns within the multi-omics data and allows downstream analysis such as patient classification or biormarker discovery.

## Getting started

-  Clone this repo: `git clone https://github.com/alabarga/BioMGNN/`
-  Enter the created folder: `cd BioMGNN`
-  Install requirements: `pip install -r requirements.txt`
-  Open Jupyter notebook `jupyter notebook` or VS code `code .`
-  Run [tutorial.ipynb]()
