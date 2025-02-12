﻿# Algerian-Forest-Fire-Prediction-System

### **Project Description**

This project aims to predict the likelihood of fire occurrences based on weather and environmental conditions, using machine learning algorithms. By analyzing historical weather data, such as temperature, relative humidity, wind speed, rainfall, and specific indices like FFMC (Fine Fuel Moisture Code), DMC (Duff Moisture Code), ISI (Initial Spread Index), the system can forecast the likelihood of fire across different regions.

This project is designed to help environmental agencies, fire departments, and local governments proactively manage wildfire risks and allocate resources more efficiently. The FWI prediction will help in preventing the destruction of valuable ecosystems, reduce the cost of firefighting efforts, and increase public safety.

### **Problem Statement**
Wildfires are a growing concern globally due to rising temperatures, irregular weather patterns, and climate change. Predicting the likelihood of a wildfire before it happens can save resources, lives, and ecosystems. This project uses machine learning techniques to predict whether a fire will occur in a specific region based on weather data. The goal is to build a reliable, deployable model that can give an accurate prediction of fire risk based on real-time weather parameters.

### **Objectives**
- Build a machine learning model that predicts whether a wildfire will occur based on environmental data.
- Use historical weather data to train the model and predict fire incidents across different regions.
- Develop a user-friendly web application where users can input real-time weather data and get fire risk predictions.

### **Dataset**
The dataset used for training the model includes various weather-related parameters such as:
- **Temperature** (°C)
- **Relative Humidity** (%)
- **Wind Speed** (km/h)
- **Rainfall** (mm)
- **FFMC Index**: Represents the moisture content of fine fuels.
- **DMC Index**: Represents the moisture content in deeper layers of soil and vegetation.
- **ISI Index**: Measures the intensity of fire spread.
- **Fire Classes**: Classifying regions as either fire-prone (1) or non-fire-prone (0).
- **Regions**: Specific locations, such as Bejaia and Sidi-Bel Abbes, where weather data is recorded.

### **Approach**
1. **Data Collection**: The dataset is obtained from reliable sources, including historical weather data and fire incidents in different regions.
2. **Data Preprocessing**: The data is cleaned, missing values are handled, and feature engineering is performed to extract relevant features. The data is split into training and testing sets.
3. **Model Selection**: Different machine learning models are evaluated for predicting fire risk. Hyperparameter tuning is performed to optimize the chosen models.
4. **Model Training and Evaluation**: The models are trained using historical data and evaluated based on metrics such as accuracy, precision, recall, and F1-score.
5. **Deployment**: The model is integrated into a web-based application that allows users to input weather conditions in real-time and get fire risk predictions.
6. **Monitoring and Maintenance**: The system includes a mechanism for periodically retraining the model with new data to improve accuracy over time.

### **Tools and Technologies**
- **Programming Language**: Python
- **Libraries**: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, Flask
- **Machine Learning Algorithms**: Linear Regression, Lasso, Ridge, ElasticNet
- **Web Development**: HTML, Flask (for backend)

### **Conclusion**
This end-to-end machine learning project demonstrates the practical application of machine learning techniques for wildfire prediction. By combining weather data with machine learning models, the system offers a powerful tool for fire risk prediction, which can help reduce the impact of wildfires and enhance preparedness for such disasters. The web-based deployment ensures accessibility, enabling both local authorities and the public to use the system effectively.
