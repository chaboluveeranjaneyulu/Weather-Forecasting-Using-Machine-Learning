🌦️ Weather Forecasting Using Machine Learning

📌 Project Overview
This project focuses on building a **Weather Forecasting System** using **Machine Learning** techniques. The model predicts **temperature** based on environmental factors such as humidity, wind speed, atmospheric pressure, and precipitation.

A synthetic dataset is generated and used to train a **Random Forest Regression model**.

🚀 Features
- 📊 Synthetic weather data generation
- 🧹 Data preprocessing and splitting
- 🤖 Machine Learning model training
- 🌡️ Temperature prediction
- 💾 Model saving for reuse

🛠️ Technologies Used
- Python 🐍
- Pandas
- NumPy
- Scikit-learn


⚙️ How It Works

1️⃣ Data Generation
- Generates 1000 days of synthetic weather data
- Uses NumPy random functions
- Ensures realistic value ranges

2️⃣ Data Preparation
- Features (X): humidity, wind_speed, pressure, precipitation  
- Target (y): temperature  

3️⃣ Model Training
- Algorithm: Random Forest Regressor  
- Train-test split: 80% / 20%  

4️⃣ Model Saving
- Saved using Joblib:

  

▶️ How to Run the Project

Step 1: Install Dependencies

pip install pandas numpy scikit-learn joblib


Step 2: Run the Script

python main.py


Step 3: Output Files
- synthetic_weather_data.csv  
- weather_prediction_model.pkl  


📈 Model Details
- Algorithm: Random Forest Regressor  
- n_estimators = 100  
- random_state = 42  

🔮 Future Improvements
- Use real-world datasets 🌍  
- Implement time-series forecasting (ARIMA, LSTM)  
- Deploy using Flask/Django  
- Add data visualization dashboards  
