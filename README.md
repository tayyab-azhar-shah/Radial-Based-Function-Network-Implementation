# Radial Basis Function Network

This repository contains a from-scratch implementation of a Radial Basis Function (RBF) neural network.

# Features
- K-means–based RBF center selection
- Automatic sigma estimation
- Ridge-regularized least squares output layer
- Multi-output regression support
- Proper train/test separation and scaling

# Dataset
- UCI Concrete Compressive Strength dataset

# Experiments
Three model capacities were evaluated:
- Small (20 RBF centers)
- Medium (50 RBF centers)
- Deep (100 RBF centers)

Performance was evaluated using Mean Squared Error (MSE) and Predicted v True graphs.

# Requirements
- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn

# Usage
Run the notebook to reproduce all experiments and plots.
