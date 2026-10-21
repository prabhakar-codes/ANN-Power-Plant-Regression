# ANN-Based Power Plant Energy Prediction

## Overview

This project uses an Artificial Neural Network (ANN) implemented with PyTorch to predict the electrical power output of a power plant based on environmental operating conditions.

## Objectives

* Understand ANN-based regression.
* Apply data preprocessing and feature standardization.
* Train a neural network using PyTorch.
* Evaluate regression performance using appropriate metrics.

## Dataset

The dataset contains the following input features:

* **AT:** Ambient Temperature
* **V:** Exhaust Vacuum
* **AP:** Ambient Pressure
* **RH:** Relative Humidity

**Target variable:** PE — Electrical Power Output.

## Technologies Used

* Python
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Load and explore the dataset.
2. Preprocess the data.
3. Split the dataset into training and testing sets.
4. Standardize the input features.
5. Build and train an ANN regression model.
6. Evaluate the model using regression metrics.
7. Compare actual and predicted power output.

## How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/ANN-Power-Plant-Regression.git
cd ANN-Power-Plant-Regression
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook ANN_Regression.ipynb
```

## Results

Model performance metrics and prediction visualizations can be added after running the notebook.

## Author

Prabhakar Kumar Prajapati
