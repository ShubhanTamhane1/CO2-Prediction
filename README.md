## 🚗 CO₂ Emissions Prediction Using Random Forest Regressor

This project leverages a **Random Forest Regressor** to predict the amount of **CO₂** emissions a car produces based on key vehicle features. The model utilizes data points such as engine size, fuel type, transmission type, and mileage (mpg) to generate accurate predictions. Additionally, **ggplot2** is used for data visualization, helping uncover hidden trends and patterns in vehicle emissions.

This model has significant applications in both the **automotive industry** (for fuel efficiency and emissions optimization) and the **environmental sector** (for regulatory compliance and sustainability initiatives).

## 📌 Features
 - Cleaning and preparing car emissions data for modeling 
 - Uncovering hidden trends and relationships between variables using **gplot2**
 - Implementing a Random Forest Regressor to accurately predict CO₂ Emissions by car
 - Assessed model using **Mean Squared Error, Mean Absolute Error, and R² Score**
 
 ## 📡 Technologies Used
  - **Programming Language: R**
  - Libraries and Tools:
    - R-Studio
    - R-Markdown
    - Dplyr
    - Car
    - Random Forest
    - ggplot2

## 📂 Dataset
The dataset features various attributes related to vehicle emissions
 - Target: **CO₂ Emissions (g/km)**
 - Predictors:
  - Fuel Type
  - Transmission Type
  - Gas Mileage
  - Engine Size
  - Make 
  - Car Type 

**Source**: https://www.kaggle.com/datasets/bhuviranga/co2-emissions
  
## 📊 Results:
- **R²  Score**: 99.4%
- MAE: 3.2

**Key Insights**: 
 - Engine Size (L) and Number of Cylinders were highly correlated with each other, causing collinearity issues
 - The type of Fuel and Gas Mileage (mpg) were the most important features 
 - Cars with lower gas mileage result in the **highest CO₂ emissions**
 - Economy brands had the **highest CO₂ emissions**
 - Automatic sequential cars had the **highest CO₂ emissions**
 - Sedans had the **highest CO₂ emissions**
 
 **Possible Future Improvements**
  - Number of passengers
  - Terrain of drive