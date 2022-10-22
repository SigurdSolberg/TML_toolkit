# Library for topological machine learning.

A library developed as a project in the course INF367 - Topological Machine learning at UiB. 

### Avaliable with PyPi
 - https://pypi.org/project/TML-toolkit/

### Functionality

1. Graph Fitting and Graph Topology Learning

     1. SOM - Self Organizing Maps
     2. GMM - Gaussian Mixture Models
     3. GGG - Generative Gaussian Graphs
     4. RGM - Reeb Graph Mapper

2. Persistent Homology and Vectorizations

     1. Rips Complex
     2. Persistence Images
     3. Persistence Landscapes
     4. PersLay

3. Topological Neural Network

     1. Topological Autoencoder
     2. Topology Layer

### Packaging_tutorial

#####├── pyproject.toml

#####├── README.md

#####├── setup.py

#####├── src/

#####│   ├── GF/

#####│   │   ├── __init__.py

#####│   │   ├── GGG.py

#####│   │   ├── GMM.py

#####│   │   ├── GNG.py

#####│   │   ├── GraphTools.py

#####│   │   ├── RGM.py

#####│   │   └── SOM.py

#####│   ├── PersistentHomology/

#####│   │   ├── __init__.py

#####│   │   ├── FilteredSimplicialComplexes.py

#####│   │   ├── PersistenceDiagram.py

#####│   │   ├── PersistenceImage.py

#####│   │   ├── PersistenceLandscapes.py

#####│   │   ├── PersLay.py

#####│   │   └── TopologicalAutoencoder.py

#####│   ├── Examples/

#####│       └── examples.py

#####├── __init__.py

#####├── main.py
