# AISE4010-Project-Smart-Meters

## Dataset Setup

The dataset is too large for GitHub, so you'll need to download it separately.

1. Download the [London Smart Meters dataset](https://zenodo.org/records/4656091).
2. Find the file `london_smart_meters_dataset_without_missing_values.tsf` (extract it if needed).
3. Put it in the same folder as the Jupyter notebook.
4. Run the notebook!

**Note:** The dataset is included in `.gitignore` so it won't be uploaded to GitHub.

## Project Overview

This project investigates deep learning approaches for short-term electricity demand forecasting using the London Smart Meters dataset.

The objective is to predict the next 24 hours of electricity consumption using the previous 168 hours (7 days) of observations. We compare traditional forecasting baselines with several neural network architectures to evaluate predictive accuracy, computational efficiency, and generalization across different seasonal periods.

The project is developed for AISE 4010: Deep Learning for Time Series at Western University.

### Models Evaluated

- Persistence baseline
- Seasonal Naive baseline
- Multilayer Perceptron (MLP)
- Convolutional Neural Network (CNN)
- Recurrent Neural Network (RNN)
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
- Temporal Convolutional Network (TCN)