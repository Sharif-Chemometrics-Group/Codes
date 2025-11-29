***GC-IMS Data Analysis and CNN Classification Pipeline***

A comprehensive Jupyter Notebook pipeline for the analysis of Gas Chromatography-Ion Mobility Spectrometry (GC-IMS) data. The workflow covers raw data preprocessing, training a Convolutional Neural Network (CNN) for classification, and interpreting model decisions using advanced visualization techniques like Saliency Maps and Principal Component Analysis (PCA).

GC-IMS data matrices were converted into 2D heatmap images before being fed into the CNN. This workflow not only leverages powerful image-based deep learning approaches but also drastically reduces data volume, from approximately 7 GB in raw matrix form to about 10 MB as images. Such compression simplifies data handling and storage, reduces input/output overhead, and improves computational efficiency during model training, while still preserving the essential structural information needed for accurate classification.

***Note:*** Code for model trainig based on original `npy` matrix instead of `jpg` has been added. The code contains matrix resizing for reducing data volume and input/output overhead. 




