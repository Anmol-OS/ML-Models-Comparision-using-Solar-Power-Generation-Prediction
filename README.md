# Solar Power Generation Prediction
This project analyzes and models solar power generation from two different plants. Using provided weather and generation data, the goal was to build a machine learning model that can accurately predict the amount of usable power generated.

### Project Overview
The project was completed as part of the Round 2 task for the GDG (Google Developer Groups) 2nd Year Core Team selections.

### Methodology
The approach for this project followed a standard machine learning workflow:

1. Data Loading and Preprocessing: The provided generation and weather data from both plants were loaded, cleaned, and merged.

2. Exploratory Data Analysis (EDA): The data was explored to understand the relationships between different variables. A key step was the correlation analysis, which showed a strong link between irradiation, module temperature, and power output. Additionally, a linear trend was noticed between irradiation and AC power suggestion regression models.

3. Model Training: Different models—Linear Regression, Decision Tree, and Random Forest—were trained and evaluated. The Random Forest model proved to be the most effective for this task.

4. Prediction: The final model was used to predict AC power generation based on new weather conditions.
