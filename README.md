# Implementation of PCA on Nutrient Database
Principal Component Analysis is a statistical technique used for reducing the dimensionality of datasets and increasing the interpretability of the same. It is a way of identifying patterns in data and expressing it in such a way so as to highlight their similarities and differences.

Here, PCA has been implemented upon the USDA National Nutrient database to identify the key nutrients contributing to different food products. After pre-processing and cleaning the data, we have standardized the values and computed the covariance matrix for the same. Eigenvalues and eigenvectors have been evaluated, sorted, and the most significant components that contribute to explaining the variance maximally have been identified. We have computed a Principal Component matrix which projects the original data onto the new subspace. The results have been assessed graphically for better data visualization. Through this model, we have successfully reduced the dimensionality of the data from 21 to 12 components that explain a cumulative variance of about 92%

The database has been obtained from https://data.world/craigkelly/usda-national-nutrient-db

The database is also available in the repository as a csv file.
