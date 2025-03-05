# Automated-Water-Quality-Prediction-and-Monitoring-using-AI-ML
# Water Quality Prediction System

## Overview

This project introduces a novel system for water quality prediction by integrating sensor data, satellite imagery, and weather information. Leveraging machine learning (ML) and explainable artificial intelligence (XAI), we develop an interpretable model that alerts users in real-time through a mobile interface, enhancing community-driven environmental monitoring.

The system utilizes an ensemble model combining:

CNN for image data processing

Random Forest for structured data analysis

Transfer Learning for optimizing deployment in low-resource environments

Our results demonstrate high accuracy and user interpretability, facilitating better decision-making in water safety.

## Features

*Real-time Water Quality Monitoring:* Combines multiple data sources for accurate assessment.

*Explainable AI (XAI):* Uses Grad-CAM to visualize CNN-based predictions.

*Mobile Interface:* Alerts users and allows community-driven data collection.

*Scalability & Flexibility:* Designed for deployment in diverse environments.

## Methodology

### Data Collection and Preprocessing

*Sensor Data:* Turbidity, pH, and conductivity readings obtained via IoT sensors, normalized for ML compatibility.

*Satellite Imagery:* CNN-based pollutant detection with pre-filtering and resizing.

*Weather Data:* Rainfall and temperature variables accessed via APIs to support seasonal analysis.

### Model Architecture

*CNN for Image Data:* Trained with transfer learning to detect pollutants.

*Random Forest for Structured Data:* Enhances prediction accuracy using sensor and weather data.

*Ensemble Model:* Assigns prediction weights based on data quality.

### Explainability and Alerts

*Grad-CAM:* Provides visual explanations for CNN predictions.

*Mobile App Alerts:* Notifies users when contamination thresholds are exceeded.

## Results & Analysis

*Bar Chart:* Water quality predictions with a higher count of 'Clean' classifications.

*Histogram:* Distribution of turbidity values, peaking around 0, 80, and 100.

*Scatter Plot:* Relationship between turbidity levels and water quality predictions.
