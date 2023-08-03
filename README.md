# scRNAseq
Analysing 10x genomics PBMC dataset, employing different types of predictive techniques for cellular classification

The main libaries that were used in this analysis included - Scanpy, Matplotlib, Numpy, TensorFlow and Scikit-learn. The analysis was broken up into 

    Preprocessing and Quality Control
        Description: This step includes reading the raw data, filtering cells based on quality metrics, and normalizing the data.
    Feature Selection
        Description: This step identifies highly variable genes in the dataset.
    Dimensionality Reduction
        Description: This step uses PCA and UMAP to reduce the dimensionality of the dataset.
    Clustering
        Description: This step identifies clusters of cells based on their gene expression profiles.
    Differential Expression Analysis
        Description: This step identifies genes that are differentially expressed between clusters.
    Machine Learning classification
        Description: Using an autoenconder, random forest and KNN classification techniques with CV and model evaluation 
