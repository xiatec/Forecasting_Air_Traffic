# Air Traffic Delay Prediction Models

This repository contains machine learning models for predicting air traffic delays at different levels: flight-level, airport-level, and network-level.

## Models

1. Random Forest: Predicts arrival delays for individual flights
2. LSTM: Predicts aggregated arrival and departure delays for a single airport
3. DST-GAT: Predicts aggregated arrival and departure delays for all airports in a network

## Data

The project uses EUROCONTROL R&D data (not provided) and airport coordinates for the top 50 European airports.

## Dependencies

- numpy
- scipy
- pandas
- scikit-learn
- keras
- spektral
- tensorflow

For GPU acceleration, configure TensorFlow with CUDA-compatible NVIDIA GPU.

## Usage

1. Clone the repository
2. Install dependencies
3. Obtain EUROCONTROL R&D data
4. Run Jupyter notebooks:
   - `flight_arr_delay_rf.ipynb`
   - `airport_delay_lstm.ipynb`
   - `network_delay_gnn.ipynb`