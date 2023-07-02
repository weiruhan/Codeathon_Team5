# Predicting protein-protein interactions and networks using sequence data

:snowflake:
> Author: Weiru Han, Maryam Alavi, Coronell Tovar, Rohit Shukla, Pawan Thapaliya, Shamima Akter, Megan Mui

This project involves the application of deep learning models to predict protein-protein interactions using sequence data.

* Data source: 

> This data is collected from [STRING](https://string-db.org/cgi/download?sessionId=bnQFSPm1YRHj&species_text=Homo+sapiens) database, using **homo sapiens** as the organism of interest to restrict the data

* Feature extraction
we refer to the [(Shen 2007)](https://pubmed.ncbi.nlm.nih.gov/17360525/) using conjoint traid method in order to convert the sequence into a new feature space.

* Objectives:

    * Screening a subset of protein types for the modeling procedure.

    * Extract valuable information from protein sequence.

    * Find a model that is effective at predicting PPI and can be readily generalized to other situations.





# Pipeline

1. Combine all data information from the data source
2. Exploratory data analysis
    * Discover and visualzie the data to gain the insight
3. Prepare data
    * Data preprocessing
    * Feature engineering

**Note: Data preprocessing and feature engineering should only be performed on training data in order to prevent training data leakage.  For instance, to perform principal component analysis, we first perform PCA on the training fold and then apply the principal components calculated from the training data to the validation fold in order to reduce the dimension and extract new features.**

4. Modeling

5. Prediction

6. Evaluation

