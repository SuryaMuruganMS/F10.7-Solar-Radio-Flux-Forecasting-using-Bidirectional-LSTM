# F10.7 Solar Radio Flux Forecasting using Bidirectional LSTM

## Description

This project aims to forecast F10.7 solar radio flux values using a Bidirectional LSTM (BILSTM) model. Accurate forecasting is essential for anticipating solar activity like flares and geomagnetic storms, aiding space weather preparedness.

## Project Overview

The BILSTM model processes historical F10.7 data to predict future flux values. Preprocessing steps, including data cleaning and normalization, prepare the input data for training the model. This approach helps stakeholders implement preventive measures and minimize potential disruptions.

## Problem Statement

F10.7 measures solar activity by reflecting extreme ultraviolet radiation from the Sun, crucial for predicting space weather events and understanding their impacts on communication and navigation systems. Accurate measurements are vital for reliable space weather forecasts, essential for satellite operations and power distribution.

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Libraries: numpy, pandas, matplotlib, seaborn, tensorflow, sklearn

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/f107_forecasting.git
    ```
2. Install jupiter:
    ```sh
    pip install jupyter
    ```
3. Run the notebook:
    ```sh
    jupyter nbconvert --to notebook --execute surya_notebook.ipynb
    ```
