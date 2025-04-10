# Hybrid-GNN-VAE-GRU-Model-for-fraud-detection
Hybrid GNN-VAE-GRU for Real-Time Fraud Detection is a robust  deep learning framework designed to detect fraudulent credit card transactions
The model leverages a hybrid architecture that combines Graph Neural Networks (GNNs), Variational Autoencoders (VAEs), and Gated Recurrent Units (GRUs) to capture spatial, latent, and temporal dependencies within transaction data.

Key features include:

Feature Attention Module: Dynamically weights input features based on importance.

Dynamic Graph Construction: Builds graphs per batch using cosine similarity to reflect changing relationships between transactions.

Multi-layer GNN with Residual Connections: Learns rich representations of transaction graphs.

Bidirectional GRU: Captures forward and backward temporal dependencies.

VAE Decoder: Reconstructs input to model underlying transaction patterns.

Auxiliary Classifier: Guides training by distinguishing fraud from normal behavior.

Stratified Batching: Maintains class distribution for effective training.

The system is built and tested on the popular creditcard.csv dataset and is suitable for real-time deployment in financial fraud detection pipelines.

