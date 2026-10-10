# Predict Energy Consumption with Machine Learning

## 📌 Project Overview
This project uses regression-based machine learning to predict daily/hourly energy usage. By analyzing factors such as temperature, humidity, time of day, and day of the week, the model identifies consumption patterns to help reduce operational costs and promote energy conservation.

## 📊 Methodology & Pipeline
1. **Data Generation/Preprocessing**: Simulated 1,000 hours of realistic energy consumption data based on ambient temperature, humidity, and time components.
2. **Feature Engineering**: Extracted temporal variables (`Hour`, `Month`, `DayOfWeek`, `Is_Weekend`).
3. **Model Development**: Trained a **Random Forest Regressor** model using an 80/20 train-test split.
4. **Evaluation**: Evaluated performance using RMSE, MAE, and $R^2$ Score.

## 🛠️ Tools & Libraries
- Python 3
- Pandas & NumPy
- Scikit-Learn
- Matplotlib & Seaborn
- Google Colab

## 📁 Repository Structure
- `predict_energy_consumption.ipynb` : Main Jupyter Notebook with data processing and model training
- `energy_consumption_data.csv` : Generated dataset used for training
- `energy_prediction_result.png` : Visualization of Actual vs. Predicted energy values
- `README.md` : Documentation
