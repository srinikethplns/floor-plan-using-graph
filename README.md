# Floor-plan-using-graph

This project involves loading, analyzing, and processing a dataset of annotated graphs representing various floor plans. These graphs are used to train a model for floor plan generation using Graph Convolutional Networks (GCNs) in PyTorch Geometric. The dataset contains nodes representing rooms and edges representing the spatial relationships between them.

Features
Graph Loading: Load the dataset of floor plans stored in .pkl files, where each graph describes a house layout.
Graph Analysis: Extract node and edge information from each graph, where nodes represent rooms (e.g., kitchen, bathroom) with attributes such as room size, centroid coordinates, and type, and edges represent distances between rooms.
GCN Compatibility: Ensure that the dataset is compatible with training a GCN to learn spatial relationships between rooms and generate new floor plans.
PyTorch Geometric Integration: The project leverages PyTorch Geometric for building and training GCNs, making the graphs suitable for deep learning tasks.
Data Exploration: Perform initial exploratory analysis on the dataset, including node and edge inspection, to ensure the integrity and usability of the graphs for model training.
