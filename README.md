# ANN neural network for brain cancer
Brain Cancer Classification via Gene Expression Analysis
Project Overview
This repository contains an Artificial Neural Network (ANN) implementation designed to classify brain tumor subtypes using gene expression data. The project utilizes the GSE50161 dataset, which consists of mRNA expression profiles (microarrays) for various brain cancer types and normal tissue samples.

# Dataset
The GSE50161 dataset provides high-dimensional genomic data. The primary objective is to accurately categorize samples into their respective clinical classes:

Ependymoma

Glioblastoma

Medulloblastoma

Pilocytic Astrocytoma

Normal Brain Tissue

# Model Architecture
Due to the high dimensionality of the feature set, the model architecture focuses on regularization and efficient feature mapping:

Input Layer: High-dimensional vectors representing gene expression levels.

Hidden Layers: Fully connected layers with ReLU activation.

Regularization: Integration of Dropout layers and Batch Normalization to prevent overfitting and improve convergence.

Optimization: Adam optimizer with Sparse Categorical Crossentropy loss.

Callbacks: Implementation of EarlyStopping and ReduceLROnPlateau for dynamic training adjustment.

# Requirements
Python 3.x

TensorFlow / Keras

Pandas / NumPy

Scikit-learn

# Performance
The model demonstrates the effectiveness of deep learning in bioinformatics for identifying complex patterns in genomic data. Detailed metrics regarding accuracy, precision, and recall are documented within the analysis notebook.
