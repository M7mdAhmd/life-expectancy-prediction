# 🌍 Life Expectancy Prediction:

This project predicts life expectancy using **machine learning** and **deep learning** techniques. By analyzing a comprehensive dataset from the World Health Organization (WHO), we explore how health, economic, and environmental factors influence life expectancy globally.  

---

## 📊 **Dataset Overview**  
The dataset includes:  
- **Health Metrics**: Adult mortality, infant deaths, BMI.  
- **Economic Indicators**: GDP, income composition.  
- **Environmental Factors**: Immunization rates, healthcare expenditure.  
- **Target Variable**: Life expectancy (in years).  

---

## 🔍 **Exploratory Data Analysis (EDA)**  
- **Missing Values**: Identified and addressed gaps in the data.  
- **Distributions**: Analyzed feature distributions using histograms.  
- **Correlations**: Found strong relationships between features like adult mortality, BMI, and life expectancy.  

---

## 🛠️ **Data Preprocessing**  
- Handled missing values using mean (numerical) and mode (categorical).  
- Encoded categorical variables with one-hot encoding.  
- Scaled features for the neural network.  
- Split data into 80% training and 20% testing sets.  

---

## 🤖 **Modeling Approaches**  

### 1. **Linear Regression (scikit-learn)**  
- **Evaluation Metrics**: MSE, MAE, RMSE.  
- **Visualization**: Scatter plot of actual vs. predicted values with a regression line.  

### 2. **Neural Network (PyTorch)**  
- **Architecture**:  
  - Input layer: Matches feature count.  
  - Hidden layers: 64 and 32 neurons.  
  - Output layer: Single neuron for regression.  
- **Training**:  
  - Loss: Mean Squared Error (`MSELoss`).  
  - Optimizer: Adam (learning rate = 0.001).  
  - Epochs: 100.  
- **Evaluation**: Test MSE calculated.  

---

## 🎯 **Conclusion**  
The project demonstrates the effectiveness of both traditional and modern techniques in predicting life expectancy. While the neural network captures complex patterns, linear regression offers simplicity and interpretability.  

---

By predicting life expectancy, we aim to contribute to a healthier, more equitable world. 🌟  