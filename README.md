# Smart-Bus-Arrival-Forecasting-System
TransitSense is a machine learning-based web application that predicts bus arrival times using route, weather, traffic, and time-related data. Built with Python, Flask, Streamlit, MySQL, XGBoost, and Random Forest, it estimates arrival time, travel duration, and delays to support smarter public transportation.
# 🚌 TransitSense: Intelligent Bus Arrival Time Prediction System Using Machine Learning

## 📌 Overview

TransitSense is a Machine Learning-based web application designed to predict bus arrival times accurately using historical transportation data and contextual features. The system analyzes route information, weather conditions, traffic density, and temporal factors to estimate arrival time, travel duration, and expected delays.

The application is developed using Flask and Streamlit for the frontend and backend, while machine learning models such as XGBoost and Random Forest are used to generate highly accurate predictions.

---

# 🚀 Features

- User Registration & Login
- Interactive Dashboard
- Manual Route & Bus Stop Input
- Weather & Traffic Information Input
- Bus Arrival Time Prediction
- Expected Delay Prediction
- Estimated Travel Time
- Bus Status (On Time / Slight Delay / Heavy Delay)
- Prediction History
- Responsive Premium UI
- Secure Database Storage

---

# 🛠 Technologies Used

### Programming Languages

- Python
- HTML
- CSS
- JavaScript

### Frameworks

- Flask
- Streamlit

### Machine Learning

- XGBoost Regressor
- Random Forest Regressor
- Scikit-learn

### Database

- MySQL

### Libraries

- Pandas
- NumPy
- Matplotlib
- Joblib
- Pickle

---

# 📂 Project Structure

```text
TransitSense/

│
├── frontend/
│   ├── app.py
│   ├── templates/
│   ├── static/
│
├── backend/
│   ├── models/
│   ├── preprocessing/
│   ├── saved_models/
│   ├── evaluation/
│   └── app.py
│
├── database/
│
├── docs/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 📊 Machine Learning Workflow

```
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Feature Scaling
      │
      ▼
Model Training
      │
      ▼
Model Selection
      │
      ▼
Prediction
      │
      ▼
Store Results
```

---

# 📈 Model Evaluation

The project is evaluated using standard regression metrics:

- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- R² Score

Generated visualizations include:

- Prediction vs Actual Plot
- Residual Plot
- Feature Importance Graph
- Error Distribution

---

# 📥 Input Parameters

Users manually enter:

- Route ID
- Bus Stop ID
- Latitude
- Longitude
- Temperature
- Humidity
- Weather Condition
- Traffic Density
- Day Type
- Time Block
- Hour
- Minute
- Bus Speed
- Distance to Next Stop
- Previous Stop Delay
- Road Condition
- Peak Hour

---

# 📤 Output

The system predicts:

- Estimated Bus Arrival Time
- Expected Delay
- Estimated Travel Time
- Bus Status
- Selected Machine Learning Model

---

# 📸 Screenshots

- Login Page
- Dashboard
- Prediction Page
- Prediction Results
- History Page
- Reports

---

# 💡 Future Enhancements

- Live GPS Tracking
- Google Maps Integration
- Real-Time Traffic API
- Weather API Integration
- Deep Learning Models (LSTM, GRU, Transformer)
- Mobile Application
- Route Optimization
- Real-Time Notifications

---

# 🎯 Applications

- Smart City Transportation
- Public Transit Systems
- Urban Mobility Solutions
- Passenger Information Systems
- Traffic Management
- Intelligent Transportation Systems (ITS)

---

# 👩‍💻 Developed By

**Poodu Deepika**

Final Year B.Tech (Computer Science & Engineering - Artificial Intelligence)

---

# ⭐ If you found this project useful

Please consider giving this repository a ⭐ on GitHub.
