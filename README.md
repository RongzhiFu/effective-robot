Dimensionality Reduction-Based Hyperspectral Image Classification Using a Hybrid Quantum Parallel Neural Network

This project implements a hybrid quantum-classical neural network (HQCNN) for hyperspectral image classification using the Pavia University dataset. The model combines classical convolutional layers with quantum layers to enhance feature extraction and classification performance.

Features
Quantum-Classical Hybrid Architecture: Combines classical CNN layers with quantum circuits using PennyLane
Dynamic Feature Reduction: Uses F-norm and PCA for efficient dimensionality reduction
Spatio-Spectral Feature Extraction: Combines spectral and spatial features
Training Logging: Automatically saves training metrics to Excel files
Three Model Architectures:
Fully Connected Neural Network (FNN)
Convolutional Neural Network (CNN)
Quantum Convolutional Neural Network (QCNN)

Requirements
Python 3.12.7
TensorFlow 2.19.0
PennyLane
scikit-learn
scipy
numpy
pandas
matplotlib

Dataset
All hyperspectral image datasets used in this study (Indian Pines, Salinas, and Pavia University) are publicly available from the Hyperspectral Remote Sensing Scenes database maintained by the University of Pavia. The complete datasets including imagery and ground truth labels can be accessed through the permanent repository URL:https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes

Usage

Run the Jupyter notebook.ipynb which contains:
Data Loading and Preprocessing:
Load and explore hyperspectral data
Filter unlabeled pixels
Prepare training/test sets

Feature Extraction:
Dynamic F-norm spectral reduction
PCA dimensionality reduction
Spatial feature extraction
