# Real-Time-Data-Analysis-in-Python3
This repository focuses on doing real-time data analysis using Python3.

The real-time data analysis of EEG signals is conducted. 
The real-time EEG signals were caught by OpenVibe3.5.0 software with an inbuilt Lab Streaming Layer (LSL). The data was then imported to Jupyter Notebook by enabling LSL in OpenVibe software.

After importing data, necessary parameters of it such as the number of channels, length of data, etc. were measured. 
A proper functioning pipelining was done to ensure the efficiency of the program while carrying out different processes. Pipelining majorly involved the creation of empty arrays, importing data chunks into them, carrying out necessary functions, exporting data to another empty array, and then clearing the previous array.

This pipeline helped in the smooth conduction of data preprocessing, visualization, and feature extraction.

In the end, EEG signals were visualized and their Power Spectral Density (PSD) was also plotted on the graph to ensure the detailing of the analysis.

Feature extraction/selection was based on research papers and they have been applied as it is.
Relative Bandpower of Theta and Alpha waves were calculated as the features of the preprocessed data.

Overall, this project aims at real-time analysis of the EEG data which may be pivotal in carrying out necessary neuroscience research.
