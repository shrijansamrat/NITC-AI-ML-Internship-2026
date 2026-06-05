# Week 03 – Battery SOC Estimation using GRU

## Objective

Develop a Deep Learning model for Battery State of Charge (SOC) estimation using battery measurement data.

## Dataset

CALCE Battery Dataset

## Workflow

Dataset
↓
Preprocessing
↓
Feature Selection
↓
Normalization
↓
Sliding Window Creation (20 timesteps)
↓
GRU Training
↓
SOC Prediction
↓
Model Evaluation

## Features Used

* Voltage (V)
* Current (I)
* Temperature (T)

## Target Variable

* State of Charge (SOC)

## Model Architecture

* GRU Layer (64 Units)
* Dense Layer (32 Units)
* Dense Output Layer (1 Unit)

## Results

* Test MAE: 0.00633
* Actual and Predicted SOC curves closely overlap
* Model successfully captures temporal battery behavior

## Files

* week_3_nitc.ipynb
* week_3_report.pdf
* gru_soc_model.h5

