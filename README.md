# Pan-Cancer-RNA-seq-Autoencoder-Analysis
## Overview
This project involves the use of an autoencoder neural network to analyze pan-cancer RNA-seq data. The goal is to learn a compressed representation of the RNA sequencing data to identify underlying patterns associated with various types of cancer. The dataset used in this analysis is derived from the Pan-Cancer Atlas and has been pre-processed to scale the expression levels between 0 and 1.

## Dataset
The dataset can be downloaded from the following URL: Pan-Cancer RNA-seq Dataset. This file contains scaled RNA-seq gene expression data for various cancer types.

## How to Download
You can download the dataset directly from the link above or by running the following command in your terminal:

bash
Copy code
wget https://github.com/greenelab/tybalt/blob/master/data/pancan_scaled_zeroone_rnaseq.tsv.gz
## Data Preparation
Before running the analysis, ensure that the dataset is decompressed and saved in the same directory as your project files. The data file should be named pancan_scaled_zeroone_rnaseq.tsv.

## Installation and Setup
This project requires Python 3 and the following Python libraries:

Numpy
Pandas
Seaborn
Matplotlib
Keras
scikit-learn
You can install these libraries using pip:

bash
Copy code
pip install numpy pandas seaborn matplotlib keras scikit-learn
## Running the Analysis
The main analysis is performed by a Python script that follows these steps:

Data Loading: Load the RNA-seq data.
Data Preprocessing: Check for and handle missing values.
Model Definition: Define the architecture of the autoencoder.
Model Training: Train the autoencoder on the training set.
Evaluation: Evaluate the model's performance and visualize the training process.
Reconstruction: Use the trained model to reconstruct the RNA-seq data.
Analysis: Analyze the reconstruction fidelity to identify genes with significant reconstruction errors.


## Results Interpretation
The results include the training history of the autoencoder and the reconstruction error analysis. These outcomes help in understanding how well the autoencoder learned the data representation and which genes might be significant in distinguishing between different cancer types based on their reconstruction fidelity.


## Authors
Ilaha
