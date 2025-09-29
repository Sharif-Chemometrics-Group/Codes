\### Notebook of Codes for \*\*\*Vis-SWNIR Spectroscopic and Hyperspectral Imaging Sensor Integrated with Artificial Intelligence for Early Diagnosis of Breast Cancer\*\*\*



This notebook implements and evaluates four different machine learning classification models: Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Multi-layer Perceptron (MLP), and Random Forest (RF). The primary goal is to classify data loaded from `.mat` files into two categories: "HC" and "BC".


The general workflow for each model is:


1\.  Load training and testing datasets.

2\.  Define the classifier with specific hyperparameters, which were previously optimized using a Grid Search methodology.

3\.  Perform 5-fold stratified cross-validation on the training data.

4\.  Train the model on the entire training set.

5\.  Evaluate the final model on the unseen test set and generate a classification report.

