# Optical-Interconnection-Network

The aim of this project is to analyze the channel utilization of an Optical Interconnection Network. Based on the research conducted by M.F. Akay, Ç.İ. Aci and F. Abut (see References), multiple metrics were used to determine the performance of a 2-dimensional Simultaneous Optical Multiprocessor Exchange Bus (2D SOME-Bus) implementation of a multiprocessor architecture. 

## Datasets:

The .csv file used in this project contains 640 samples, each indicating a performance measurement. Additional information about each feature can be found in the optical_data_features.txt file. Both files are located in the data folder.

## Results:

This project utilizes a Deep Neural Network (DNN) to predict the Channel Utilization trends. The original dataset contains 640 samples. However, 10 of them were outliers in that those samples indicated the Channel Utilization (dependent variable) was over 100%.

The actual results are illustrated and found in the cleaned version of the project (Optical_Interconnection_Network_DNN_cleaned.ipynb). However the original, raw dataset was used to illustrate the effects of random noise and interference in a seperate script (Optical_Interconnection_Network_DNN_original.ipynb).

## References:

- https://archive.ics.uci.edu/ml/datasets/Optical+Interconnection+Network+
- Aci, Ç.İ. & Akay, M.F. A hybrid congestion control algorithm for broadcast-based architectures with multiple input queues. J Supercomput (2015) 71: 1907.
- M.F. Akay, Ç.İ. Aci, F. Abut, Predicting the Performance Measures of a 2-Dimensional Message Passing Multiprocessor Architecture by Using Machine Learning Methods. Neural Network World 71(5):1907-1931. DOI: 10.14311/NNW.2015.25.013.
