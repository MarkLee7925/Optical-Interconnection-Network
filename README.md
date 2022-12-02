# Optical-Interconnection-Network

The aim of this project was to analyze the Channel Utilization trends of an Optical Interconnection Network. Based on the research conducted by M.F. Akay, Ç.İ. Aci and F. Abut (see References), multiple metrics were used to determine the performance of a 2-dimensional Simultaneous Optical Multiprocessor Exchange Bus (2D SOME-Bus) implementation of a multiprocessor architecture. 

## Datasets:

The .csv file used in this project contained 640 samples, each indicating a performance measurement. Additional information about each feature can be found in the optical_data_features.txt file. Both files are located in the data folder.

Although the original dataset contained 640 samples, 10 of them were outliers which indicated the Channel Utilization was over 100%. To ensure more consistent results, these samples were removed for prediction. In reality, such values could indicate network congestion if there are too many devices connected which would result in greater power consumption and potential crashes.

## Models:

The following regression models were implemented in this project:

- Linear Regression (LR)
- Linear Support Vector Regression (Linear SVR)
- Kernel Support Vector Regression (Kernel SVR)
- XGBoost (XGB)
- Deep Neural Network (DNN)

For the DNN model, the actual results were illustrated and found in the cleaned version of the project (Optical_DNN_Reg_cleaned.ipynb). The original, raw dataset was used to showcase the effects of random noise and interference in a seperate script (Optical_DNN_Reg_original.ipynb). This was done for illustration purposes only.

## Dashboard:

A Power BI dashboard (OpticalBI.pbix) was created to illustrate some of the most important data and Machine Learning results at a glance.

![OptialBI](OpticalBI.jpeg)

![OpticalBI](https://user-images.githubusercontent.com/59748085/205374740-903092c3-641e-46ea-93e6-663a64d61442.JPG)



## References:

- Aci, Ç.İ. & Akay, M.F. A hybrid congestion control algorithm for broadcast-based architectures with multiple input queues. J Supercomput (2015) 71: 1907.
- https://archive.ics.uci.edu/ml/datasets/Optical+Interconnection+Network+
- M.F. Akay, Ç.İ. Aci, F. Abut, Predicting the Performance Measures of a 2-Dimensional Message Passing Multiprocessor Architecture by Using Machine Learning Methods. Neural Network World 71(5):1907-1931. DOI: 10.14311/NNW.2015.25.013.
- https://www.researchgate.net/publication/270959098_Predicting_the_Performance_Measures_of_a_2-Dimensional_Message_Passing_Multiprocessor_Architecture_by_Using_Machine_Learning_Methods
