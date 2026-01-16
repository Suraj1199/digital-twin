# Digital Twin - Vehicle Simulator Model

[![Repo](https://img.shields.io/badge/GitHub-Suraj1199%2Fdigital--twin-blue?logo=github)](https://github.com/Suraj1199/digital-twin)

## Overview
This repository aims to **learn a simulator model through neural networks**, specifically for vehicles, using Python and Jupyter Notebooks. Leveraging deep learning and robust data processing, you can train neural models to approximate vehicle dynamics and behavior from real-world or simulated data.

---

## Repository Contents

### Main Notebooks

| File | Description |
| ---- | ----------- |
| [`develop.ipynb`](https://github.com/Suraj1199/digital-twin/blob/main/develop.ipynb) | Core development notebook: contains data loading, preprocessing, and neural network architecture for vehicle dynamics modeling. |
| [`train_simulator.ipynb`](https://github.com/Suraj1199/digital-twin/blob/main/train_simulator.ipynb) | Primary training workflow notebook: use to preprocess datasets and train the neural network simulator for vehicles. |

**Note**: These are the top notebook files found. To view additional files, [search in GitHub](https://github.com/Suraj1199/digital-twin/search?q=.ipynb).

---

## Key Features

- **Neural Network Architecture**: Implements a fully-connected feedforward network (`VehicleNeuralNetwork`) with customizable hidden layers, relu activations, and dropout for regularization (PyTorch).
- **Data Preprocessing**: Includes utilities (`VehicleDataProcessor`) for cleaning, normalizing, and aligning time-series vehicle data, preparing it for supervised learning.
- **Training Pipeline**: Supports dataset splitting, scaling, mini-batch training, and model saving/loading using PyTorch and scikit-learn.
- **Visualization**: Integrates with matplotlib for performance monitoring and data exploration.

---

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Install requirements:
  ```bash
  pip install torch pandas numpy scikit-learn matplotlib
