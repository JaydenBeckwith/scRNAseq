# scRNAseq
Analysing 10x genomics PBMC dataset, employing different types of predictive techniques for cellular classification

The main libaries that were used in this analysis included - Scanpy, Matplotlib, Numpy, TensorFlow and Scikit-learn. The analysis was broken up into 

Preprocessing and Quality Control
    Reading the raw data, filtering cells based on quality metrics, and normalizing the data.
Feature Selection
    This step identifies highly variable genes in the dataset.
Dimensionality Reduction
    This step uses PCA and UMAP to reduce the dimensionality of the dataset.
Clustering
    This step identifies clusters of cells based on their gene expression profiles.
Differential Expression Analysis
    This step identifies genes that are differentially expressed between clusters.
Machine Learning classification
    Using an autoenconder, random forest and KNN classification techniques with CV and model evaluation 
