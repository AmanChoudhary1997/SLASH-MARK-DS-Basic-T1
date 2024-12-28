# Daily Weather Data Analysis

## Project Overview
This project analyzes daily weather information, focusing on temperature, precipitation, and other key metrics to derive meaningful insights. Through data exploration, feature engineering, and advanced analysis, we uncover patterns in weather trends and predict rainfall using a simple linear regression model. The analysis uses a dataset named `weather.csv`.

---

## Technology Used
- **Python**
  - **Pandas, NumPy**: Data manipulation and cleaning
  - **Matplotlib, Seaborn**: Data visualization
  - **Scikit-Learn**: Machine learning (Linear Regression, data preprocessing)
  - **Jupyter Notebook**: Code and analysis environment

---

## Dataset
The analysis uses a single dataset:

- **weather.csv**: Contains daily weather information, including MaxTemp, MinTemp, Rainfall, and more.

---

## Key Steps
### Data Preparation and Cleaning:
- Checked for missing values and inconsistencies.
- Added a new feature: **Temperature Range** = MaxTemp - MinTemp.

### Exploratory Data Analysis (EDA):
- Explored dataset structure and summary statistics.
- Visualized relationships between key variables using pair plots.

### Data Analysis:
- Calculated overall averages for MaxTemp and Rainfall.
- Identified monthly trends in average temperature and rainfall.

### Machine Learning Model:
- Built a regression model to predict Rainfall based on temperature features.
- Split the data into training and testing sets.
- Evaluated model performance using Mean Squared Error (MSE).

### Visualizations:
- Scatter plot comparing actual vs predicted rainfall values.
- Monthly trends for average rainfall and temperature.

---

## Key Insights
1. **Temperature Trends**: High correlation observed between MaxTemp and MinTemp.
2. **Rainfall Trends**: Certain months experience significantly higher rainfall.
3. **Prediction Model**: The linear regression model for rainfall prediction yielded an MSE indicating moderate accuracy.
4. **Temperature Range**: Variations in daily temperature ranges are prominent and affect rainfall.

---

## Recommendations
1. **Weather Monitoring**: Use temperature trends to anticipate rainfall and plan activities accordingly.
2. **Model Improvement**: Incorporate additional features like humidity, wind speed, and pressure to improve rainfall prediction accuracy.
3. **Seasonal Planning**: Utilize insights from monthly trends to prepare for periods of high rainfall.

---

## Author
**Name**: Aman Choudhary (Intern ID: SMI73722)  
**Email**: [amanchoudhary11189.ac@gmail.com](mailto:amanchoudhary11189.ac@gmail.com)  
**LinkedIn**: [Aman Choudhary](https://www.linkedin.com/in/aman-choudhary-61a9361a0/)  
**Portfolio**: [Aman Choudhary's Portfolio](https://amanchoudhary1997.github.io/amanchoudhary.github.io/)

