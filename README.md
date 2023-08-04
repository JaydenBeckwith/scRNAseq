# scRNAseq overview - PBMC analysis 
Analysing 10x genomics PBMC dataset, employing different types of predictive techniques for cellular classification


The main libaries that were used in this analysis included - Scanpy, Matplotlib, Numpy, TensorFlow and Scikit-learn. The analysis was broken up into 

1. Preprocessing and Quality Control

Reading the raw data, filtering cells based on quality metrics, and normalizing the data.
    
2. Feature Selection

This step identifies highly variable genes in the dataset.
    
3. Dimensionality Reduction

This step uses PCA and UMAP to reduce the dimensionality of the dataset.
    
4. Clustering

This step identifies clusters of cells based on their gene expression profiles.
    
5. Machine Learning classification

Using an autoenconder, random forest and KNN classification techniques with CV and model evaluation 
