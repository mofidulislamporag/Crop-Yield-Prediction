# 🌱 Crop Yield Prediction System

A comprehensive machine learning system for predicting crop yields based on various agricultural factors. This project analyzes historical crop data and builds predictive models to help farmers and agricultural planners optimize crop production.

## 🌟 Overview

This project implements a machine learning pipeline to predict crop yields (in tons per hectare) based on factors like:
- **Environmental conditions**: Rainfall, temperature, weather
- **Agricultural practices**: Fertilizer usage, irrigation
- **Crop characteristics**: Crop type, soil type, growing period
- **Geographical factors**: Region, soil type

The system helps in:
- Predicting crop yields for better planning
- Understanding key factors affecting productivity
- Optimizing resource allocation
- Supporting agricultural decision-making

## ✨ Features

- **📊 Comprehensive Data Analysis**: Exploratory data analysis with multiple visualizations
- **🤖 Multiple ML Models**: Random Forest, Gradient Boosting, Linear Regression, Ridge Regression
- **🔍 Feature Importance**: Identify key factors affecting crop yields
- **📈 Interactive Predictions**: Easy-to-use prediction function for new scenarios
- **🌾 Crop-specific Insights**: Detailed analysis for different crop types
- **📱 Jupyter Notebook**: Complete analysis in an interactive notebook format

## 📁 Dataset

The dataset contains the following features:

| Feature | Description | Type |
|---------|-------------|------|
| Region | Geographical region (North, South, East, West) | Categorical |
| Soil_Type | Type of soil (Clay, Loam, Sandy, etc.) | Categorical |
| Crop | Type of crop (Wheat, Rice, Maize, etc.) | Categorical |
| Rainfall_mm | Rainfall in millimeters | Numerical |
| Temperature_Celsius | Temperature in Celsius | Numerical |
| Fertilizer_Used | Whether fertilizer was used | Boolean |
| Irrigation_Used | Whether irrigation was used | Boolean |
| Weather_Condition | Weather condition during growth | Categorical |
| Days_to_Harvest | Number of days until harvest | Numerical |
| Yield_tons_per_hectare | Target variable - yield in tons/hectare | Numerical |

## 🚀 Installation

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Required Python packages



## 📈 Model Performance

The system evaluates multiple machine learning algorithms:

| Model | R² Score | RMSE | MAE |
|-------|----------|------|-----|
| Random Forest | ~0.90 | ~0.51 | ~0.41 |
| Gradient Boosting | ~0.91 | ~0.50 | ~0.40 |
| Linear Regression | ~0.91 | ~0.50 | ~0.39 |
| Ridge Regression | ~0.91 | ~0.50 | ~0.39 |

*Note: Actual performance may vary based on data and hyperparameters*

## 🔍 Key Insights

### Top Factors Affecting Yield
1. **Rainfall** - Optimal rainfall significantly impacts yield
2. **Temperature** - Different crops have different temperature preferences
3. **Fertilizer Usage** - Proper fertilization increases yield
4. **Soil Type** - Certain soils are better for specific crops
5. **Growing Period** - Longer growing periods generally produce higher yields

### Crop-specific Recommendations
- **Rice**: Requires high rainfall and longer growing periods
- **Wheat**: Performs well in moderate temperatures with proper irrigation
- **Maize**: Benefits from fertilizer and optimal temperature ranges


### Areas for Improvement
- Add more sophisticated models (Neural Networks, XGBoost)
- Include time-series analysis for seasonal patterns
- Add more agricultural features (pest control, soil pH, etc.)
- Create a web interface for easier access
- Add real-time weather data integration


## 🙏 Acknowledgments

- Dataset provided for educational purposes
- Built with popular Python data science libraries
- Inspired by the need for sustainable agricultural practices


<div align="center">

**⭐ Don't forget to star this repository if you find it helpful!**

*Helping farmers make data-driven decisions for better yields* 🌾

</div>
