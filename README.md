# Step-counter-MATLAB
This MATLAB project estimates the number of steps taken by analyzing accelerometer data. It uses signal processing techniques to detect peaks in the magnitude of acceleration, corresponding to human steps.

Features
->Reads 3-axis accelerometer data (X, Y, Z)

->Computes the magnitude of acceleration

->Applies a low-pass filter to reduce noise

->Detects peaks in the filtered signal to count steps

->Plots the filtered signal with detected steps marked

->Outputs total number of steps

Requirements
MATLAB (R2018 or later recommended)

Accelerometer data in .mat format (or modify code for .csv or other)

Customization
Adjust the sampling frequency fs according to your data.

Tune the peak detection parameters (MinPeakHeight, MinPeakDistance) for better accuracy.
