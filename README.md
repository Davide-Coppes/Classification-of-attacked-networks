# Classification-of-attacked-networks

This project aims to determine whether and how a network has been attacked using machine learning techniques. The networks under consideration are of three types: Erdős–Rényi, Barabási–Albert, and Watts–Strogatz. We characterize each network using four metrics:
- Normalized Reciprocal Maximum Degree
- Global Clustering Coefficient
- Normalized Average Path Length
- Assortativity

The types of attacks analyzed include:
- Random Failures
- Maximum-Degree Node Deletion
- Maximum-Betweenness Node Deletion

For node deletion, nodes are removed based on their centrality in the network, measured by degree and betweenness.

## Machine Learning Models
We employ two machine learning models to identify whether a network has been attacked and, if so, determine the type of attack:
- **Random Forest Algorithm**
- **Feedforward Neural Network**
