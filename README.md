# Crop and Fertilizer Recommendation System 🌱🌾

An intelligent agricultural decision support system that leverages machine learning to provide data-driven recommendations for optimal crop selection and fertilizer application based on environmental conditions and soil parameters.

## Overview

The Crop and Fertilizer Recommendation System is a comprehensive machine learning solution designed to assist farmers, agricultural consultants, and agtech companies in making informed decisions about crop cultivation and fertilizer management. The system analyzes multiple environmental and soil factors to predict the most suitable crops and recommend appropriate fertilizers for specific growing conditions.

## Key Features

### 🌾 Crop Recommendation Engine
- **Multi-factor Analysis**: Considers 7 key parameters (N, P, K, temperature, humidity, pH, rainfall)
- **22 Crop Classifications**: Supports rice, maize, chickpea, kidneybeans, pigeonpeas, mothbeans, mungbean, blackgram, lentil, pomegranate, banana, mango, grapes, watermelon, muskmelon, apple, orange, papaya, coconut, cotton, jute, and coffee
- **Balanced Dataset**: 2,200 samples with 100 instances per crop type
- **Environmental Optimization**: Recommendations based on climate and soil conditions

### 🧪 Fertilizer Recommendation System
- **Precision Agriculture**: Targeted fertilizer recommendations based on soil composition
- **7 Fertilizer Types**: Urea, DAP, 14-35-14, 28-28, 17-17-17, 20-20, and 10-26-26
- **Multi-parameter Input**: Temperature, humidity, moisture, soil type, crop type, and NPK levels
- **Cost-Effective Solutions**: Optimized fertilizer application to reduce waste and costs

### 📊 Advanced Analytics
- **Correlation Analysis**: Understanding relationships between environmental factors
- **Statistical Insights**: Comprehensive data distribution analysis
- **Visualization Tools**: Interactive plots and heatmaps for data exploration
- **Feature Engineering**: Automated encoding of categorical variables

## Prerequisites

### System Requirements
- **Python**: 3.7 or higher
- **Memory**: 4GB RAM minimum (8GB recommended)
- **Storage**: 2GB free space for datasets and models
- **Operating System**: Windows 10+, macOS 10.14+, or Linux (Ubuntu 18.04+)

### Required Libraries
```python
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=1.0.0
jupyter>=1.0.0
