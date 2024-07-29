# Image Classification Using PCA and Gaussian Kernel PCA

This project investigates the application of PCA and Gaussian kernel PCA for image feature extraction and classification. Inspired by Quan Wang's research, it compares error rates using a linear classifier and includes functions for data processing, PCA/kPCA computation, and evaluation.

## Overview

This project delves into the application of Principal Component Analysis (PCA) and
 Gaussian kernel PCA in the field of image processing and classification. Our study is inspired
 by and seeks to simulate the experiment conducted by Quan Wang in his seminal paper ”Kernel
 Principal Component Analysis and its Applications in Face Recognition and Active Shape Models”. In our study, we utilize images with pixel intensities of 168 × 192, resulting in an original
 feature vector that is 32256-dimensional. Our primary objective is to extract the nine most sig nificant features from the training data using both standard PCA and Gaussian kernel PCA, and
 subsequently record the eigenvectors.
 
 In the case of standard PCA, the extraction process only requires the eigenvectors. However,
 Gaussian kernel PCA necessitates both the eigenvectors and the training data. A significant
 part of our study involves the use of a Gaussian kernel with $σ$ = 22546 in kernel PCA. For the
 classification process, we employ the simplest linear classifier.
 Our code includes functions for loading the dataset, performing PCA and kPCA, computing a
 sparse distance matrix, and computing a sparse kernel matrix. We also implemented a function to
 compute the value of sigma used in the Gaussian kernel based on the mean distance to the nearest
 neighbors.
 
 Finally, the project presents a comparative analysis of the training error rates and testing error
 rates for standard PCA and Gaussian kernel PCA. By replicating and expanding upon Quan
 Wang’s experiment, this project aims to contribute to the ongoing discourse on image processing
 and classification, and the role of PCA methodologies within it.

 ### Additional Information

The repository also includes a `Report.pdf` that briefly explains our approach and methodology used to solve the proble

 
