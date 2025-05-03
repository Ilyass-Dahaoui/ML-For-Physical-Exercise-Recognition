# ML for Physical Exercise Recognition

This repository implements a machine learning model designed for recognizing physical exercises from multimodal time series data. The architecture leverages multiple data streams to improve recognition accuracy, processing inputs such as 3D distances, angles, landmarks, and XYZ positions. By utilizing time series analysis, the model effectively captures temporal patterns and correlations in the data, enabling real-time exercise classification. This approach aims to provide robust exercise recognition across various scenarios, integrating both spatial and temporal information for higher performance.

## Files Overview

- `ML_for_Physical_Exercise_Recognition.ipynb`: Jupyter notebook with the machine learning model for exercise recognition.
- `data/`: Contains the dataset required for training and testing the model:
  - `3d_distances.csv`
  - `angles.csv`
  - `labels.csv`
  - `landmarks.csv`
  - `xyz_distances.csv`

## Requirements

- Python 3.x
- Required libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib (optional, for visualization)

## Usage

1. Clone the repository:
`git clone https://github.com/Ilyass-Dahaoui/ML-For-Physical-Exercise-Recognition.git`
