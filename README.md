# ble-signal-movement-analysis

# BLE-Based Movement Tracking & Signal Space Analysis

## Overview

This project analyzes Bluetooth Low Energy (BLE) RSSI signals to track movement and understand spatial patterns in indoor environments.

## Problem

Indoor positioning using BLE signals is challenging due to noise, multipath effects, and signal instability.

## Data Collection

* Collected RSSI values using 3 ESP32 BLE modules
* Recorded signal strength over time for different movement patterns

## Approach

* Preprocessed noisy RSSI signals
* Performed feature engineering on signal data
* Applied Principal Component Analysis (PCA) for dimensionality reduction
* Used clustering algorithms (K-Means) to identify movement patterns

## Results

* Successfully identified distinct movement clusters
* PCA helped visualize signal space transformations
* Improved robustness against noise in RSSI signals

## Visualizations

(Add your plots here)

* PCA scatter plot
* RSSI vs time graph
* Cluster visualization

## Tech Stack

Python, NumPy, Pandas, Scikit-learn, Matplotlib

## Future Improvements

* Apply LSTM/Deep Learning for sequential modeling
* Improve accuracy using Kalman Filtering
* Real-time tracking system

## Applications

* Indoor navigation
* Smart homes
* Asset tracking systems
