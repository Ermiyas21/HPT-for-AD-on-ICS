# Comparative Analysis of Hyperparameter Optimization Techniques for Anomaly Detection in ICS

This repository contains the code, datasets, and supporting materials for the research project. The project focuses on leveraging advanced algorithms and optimization techniques to detect anomalies in ICS environments, ensuring robust, real-time solutions for critical industrial operations.

## Table of Contents
1. Overview

2. Dataset

3. Methodology

4. Results

### Overview
Industrial Control Systems (ICS) play a critical role in modern infrastructure, and their security and reliability are paramount. This project applies machine learning techniques to detect anomalies in the SwaT (Secure Water Treatment) dataset, a widely recognized ICS benchmark dataset. The study explores various anomaly detection methods, including Isolation Forest, One-Class SVM (OCSVM), Autoencoder, and LSTM, alongside optimization techniques such as Grid Search, Random Search, Bayesian Optimization, and Particle Swarm Optimization (PSO).
The goal is to identify the most effective approach for real-time anomaly detection in ICS environments while ensuring computational efficiency and practical applicability.

### Dataset
The project uses the publicly available [SwaT dataset](https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/) for ICS anomaly detection. The dataset contains 946,722 rows and 51 features, offering a rich resource for evaluating machine learning models.

Key preprocessing steps include:
**Feature Selection:** Filtering methods to select the strongest features.

**Random Sampling:** Reducing dataset size for computational efficiency.

**SMOTE (Synthetic Minority Oversampling Technique):** Addressing class imbalance to enhance anomaly detection.

### methodology 
The research evaluates the following machine learning methods:

**Isolation Forest:** Efficient tree-based anomaly detection.

**One-Class SVM (OCSVM):** Kernel-based approach for identifying deviations.

**Autoencoder:** Neural network for unsupervised anomaly detection.

**LSTM:** Recurrent neural network for time-series anomaly detection.


### Optimization Techniques
Hyperparameter tuning was performed using:

**1. Grid Search**

**2. Random Search**

**3. Bayesian Optimization (Optuna)**

**4. Particle Swarm Optimization (PSO)**

Each method was evaluated using metrics like recall, AUC, and f1 score to identify the best-performing models for ICS anomaly detection.
