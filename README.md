# Artifical-neural-network-for-regression
Artificial Neural Network (ANN) model to predict power plant energy output based on ambient variables.

# Combined Cycle Power Plant Energy Prediction

## Project Description
In this project, the Combined Cycle Power Plant (CCPP) dataset is used to predict electricity generation. The dataset contains environmental variables (Temperature, Ambient Pressure, Relative Humidity, and Exhaust Vacuum) that affect the electricity production of the power plant. The goal is to build a machine learning model that predicts the net hourly electrical energy output (EP) based on these input variables.

A Neural Network (ANN) model is trained and evaluated on this dataset for regression tasks.

## Dataset
The dataset consists of 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011) when the plant was working at full load. The features of the dataset include:

- **Features**:
  - Temperature (T)
  - Ambient Pressure (AP)
  - Relative Humidity (RH)
  - Exhaust Vacuum (V)

- **Target**:
  - Electrical Energy Output (EP)

The dataset was obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant).

## Project Setup
To run this project on your machine, follow these steps:

### Requirements
- Python 3.x
- TensorFlow
- Pandas
- Numpy
- Matplotlib

### Installation
Install the required libraries using the following command:

```bash
pip install tensorflow pandas numpy matplotlib
