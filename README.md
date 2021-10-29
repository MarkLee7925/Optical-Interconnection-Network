# Optical-Interconnection-Network

The aim of this project is to analyze the channel utilization of an Optical Interconnection Network. Based on the research conducted by M.F. Akay, Ç.İ. Aci and F. Abut (see References), multiple metrics were used to determine the performance of a 2-dimensional Simultaneous Optical Multiprocessor Exchange Bus (2D SOME-Bus) implementation of a multiprocessor architecture. 

## Datasets:

The .csv file used in this project contains 640 samples, each indicating a performance measurement (feature). Additional information about each feature can be found in the optical_data_features.txt file. Both files are located in the data folder.

Although the original dataset contains 640 samples, 10 of them were outliers which indicated the Channel Utilization was over 100%. To ensure more consistent results, these samples were removed for prediction.

## Results:

The following models were implemented in this project:

- (Multiple) Linear Regression (LR)
- Support Vector Regression (SVR)
- XGBoost (XGB)
- Deep Neural Network (DNN)

For the DNN model, the actual results are illustrated and found in the cleaned version of the project (Optical_DNN_cleaned.ipynb). The original, raw dataset was used to showcase the effects of random noise and interference in a seperate script (Optical_DNN_original.ipynb). This is done for illustration purposes only.

## References:

- Aci, Ç.İ. & Akay, M.F. A hybrid congestion control algorithm for broadcast-based architectures with multiple input queues. J Supercomput (2015) 71: 1907.
- https://archive.ics.uci.edu/ml/datasets/Optical+Interconnection+Network+
- M.F. Akay, Ç.İ. Aci, F. Abut, Predicting the Performance Measures of a 2-Dimensional Message Passing Multiprocessor Architecture by Using Machine Learning Methods. Neural Network World 71(5):1907-1931. DOI: 10.14311/NNW.2015.25.013.
- https://www.researchgate.net/publication/270959098_Predicting_the_Performance_Measures_of_a_2-Dimensional_Message_Passing_Multiprocessor_Architecture_by_Using_Machine_Learning_Methods
