# Autonomous Transmission Line Fault Detection

## Overview

This project presents an intelligent fault detection and classification framework for power transmission lines using machine learning techniques.

The objective is to detect and classify transmission line faults autonomously by combining power system simulation with data-driven analysis. A dataset was generated using MATLAB/Simulink under multiple fault conditions and used to train a Random Forest classifier.

## Project Highlights

* Classification of 11 transmission line fault types
* MATLAB/Simulink-based fault simulation
* Feature extraction using electrical parameters
* Random Forest machine learning model
* Overall classification accuracy: 73.09%

## Methodology

### Data Generation

A transmission line model was developed in MATLAB/Simulink and tested under:

* Single Line-to-Ground (SLG) faults
* Line-to-Line (LL) faults
* Double Line-to-Ground (DLG) faults
* Three-Phase faults

Different fault resistances and inception times were considered to improve model robustness.

### Feature Engineering

The system extracts 24 electrical features including:

* RMS voltages and currents
* Peak voltages and currents
* Total Harmonic Distortion (THD)
* Zero-sequence components
* Negative-sequence components
* Voltage and current imbalance factors

### Machine Learning Model

A Random Forest Classifier was trained using the generated dataset.

Results:

* Accuracy: 73.09%
* Multi-class fault classification across 11 fault categories

## Results

The model demonstrated strong performance in identifying:

* Line-to-Line faults
* Three-phase faults
* Ground faults under varying fault resistances

## Future Scope

* Deep Learning (LSTM) based classification
* Real-time Hardware-in-the-Loop testing
* Integration with smart grid infrastructure
* Renewable energy grid fault analysis

## Authors

* Siyon Peter
* Sanjeev Mohan
* Venkitesh Vinod
* Sharun Putta P

## Report

The complete project report is available in the `report` directory.
