# Heart Disease Prediction with Severity Levels

An AI-powered system for predicting heart disease risk and classifying severity levels. The platform integrates neural networks, K-means clustering, and gradient descent for accurate, real-time risk assessment presented on an interactive dashboard.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Data & Preprocessing](#data--preprocessing)
- [Model Architecture](#model-architecture)
- [Dashboard Demo](#dashboard-demo)
- [Results](#results)
- [Future Work](#future-work)


---

## Project Overview

This project classifies heart disease severity and predicts risk levels using a blend of supervised and unsupervised machine learning models.
- Multi-class severity classification
- Integration of neural networks and K-means clustering
- Real-time dashboard for interactive risk analysis

## Features

- Risk prediction for heart disease severity using neural networks
- Robust data preprocessing pipeline
- Severity clustering (K-means)
- Gradient descent optimization
- Django-powered dashboard with HTML/CSS/JavaScript

## Technology Stack

- Python
- Django
- Machine Learning: Neural Networks, K-means Clustering, Gradient Descent
- Data Filtering, Prompt Engineering
- HTML/CSS / JavaScript

## Getting Started

### Prerequisites

- Python 3.8+
- Django 3.2+
- Required Python packages (see `requirements.txt`)

### Installation

git clone 
cd heart-disease-prediction
pip install -r requirements.txt
python manage.py runserver

Access the dashboard at `http://localhost:8000/`.

## Data & Preprocessing

- Example dataset: UCI Heart Disease Dataset (or custom data)
- Data cleaning, filtering, and normalization via pandas/numpy
- Feature engineering for severity scoring
- Outlier removal and missing value imputation

## Model Architecture

- Multi-layer neural network for severity prediction
- K-means clustering for risk grouping
- Gradient descent for optimization

## Dashboard Demo

- Real-time dashboard for patient data input and risk assessment
- Visualization of predictions and clusters

## Results

- High-accuracy risk prediction across severity levels
- Performance metrics (accuracy, F1-score, confusion matrix) available in `/results`

## Future Work

- Expand the dataset and validation
- Integrate additional health metrics (e.g., ECG readings)
- Deploy as a cloud-hosted API

