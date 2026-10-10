# Predict Energy Consumption with Machine Learning

> **Project Target:** Predict hourly power consumption based on temporal features and weather conditions to optimize energy usage and reduce operational costs.

## 📌 Project Overview
This project applies regression-based machine learning to predict hourly energy consumption. By analyzing ambient factors such as temperature, humidity, and time components, the model uncovers consumption patterns that assist utilities and businesses in energy conservation and resource optimization.

## 🔑 Key Insights & Business Findings
- **Temperature as a Primary Driver:** Ambient temperature has a strong positive correlation with energy usage, primarily due to peak cooling/heating demands (HVAC loads) when temperatures deviate from baseline levels.
- **Temporal Patterns:** Energy demand fluctuates predictably based on the hour of the day and whether it is a weekday or weekend, showing significant drops during weekends.
- **Model Performance:** The **Random Forest Regressor** successfully captured non-linear relationships in the data, achieving a high $R^2$ score and demonstrating robust predictive accuracy for operational planning.

## 📊 Methodology & Pipeline
1. **Data Generation & Preprocessing**: Simulated 1,000 hours of realistic hourly energy consumption data based on temperature, humidity, and time variables.
2. **Feature Engineering**: Extracted temporal components (`Hour`, `Month`, `DayOfWeek`, `Is_Weekend`) to capture cyclic behavioral patterns.
3. **Model Development**: Trained a Random Forest Regressor using an 80/20 train-test split.
4. **Evaluation**: Evaluated performance using Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and $R^2$ Score.

## 🛠️ Tools & Libraries
- Python 3
- Pandas & NumPy
- Scikit-Learn
- Matplotlib & Seaborn
- Google Colab

## 📁 Repository Contents
- `predict_energy_consumption.ipynb` : Main Jupyter Notebook containing data pipeline and model training
- `energy_consumption_data.csv` : Dataset used for training and testing
- `energy_prediction_result.png` : Visualization chart comparing actual vs. predicted energy values
- `README.md` : Project documentation
