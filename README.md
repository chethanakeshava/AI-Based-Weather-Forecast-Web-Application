#  AI-Based Weather Forecast Web Application

A **Django-based weather forecasting web application** that displays real-time weather data using the **OpenWeatherMap API** and predicts future weather conditions using **Machine Learning models**.
The application also visualizes temperature trends with **Chart.js**.

---

## 📌 Features

* 🌍 Search weather by **city name**
* 🌡 Displays **current temperature and weather conditions**
* 💧 Shows **humidity, pressure, wind speed, cloud cover, and visibility**
* 📈 **Temperature trend visualization** using Chart.js
* 🤖 **Machine Learning models** to predict:

  * Rain prediction (Random Forest Classifier)
  * Future temperature prediction
  * Future humidity prediction
* ⏱ Hourly forecast display
* 🎨 Dynamic weather background based on weather condition

---

## 🛠 Technologies Used

### Backend

* Python
* Django

### Machine Learning

* Scikit-learn
* Random Forest Algorithm
* Pandas
* NumPy

### Frontend

* HTML
* CSS
* Bootstrap Icons
* JavaScript
* Chart.js

### API

* OpenWeatherMap API

---

## 📂 Project Structure

```
weather-forecast-app
│
├── weather_app
│   ├── views.py
│
├── templates
│   └── weather.html
│
├── static
│   ├── css
│   │   └── styles.css
│   ├── js
│   │   └── chartSetup.js
│   └── img
│
├── weather.csv
├── manage.py
├── requirements.txt
└── README.md
```

---

## ⚙ Installation and Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/yourusername/weather-forecast-app.git
```

```
cd weather-forecast-app
```

---

### 2️⃣ Install Required Libraries

```
pip install -r requirements.txt
```

---

### 3️⃣ Add Your API Key

Create a `.env` file or add your API key inside the project.

Example:

```
WEATHER_API_KEY=your_api_key_here
```

You can get an API key from:
https://openweathermap.org/api

---

### 4️⃣ Run the Django Server

```
python manage.py runserver
```

Then open in browser:

```
http://127.0.0.1:8000
```

---

## 📊 Machine Learning Models Used

### 🌧 Rain Prediction Model

* Algorithm: **Random Forest Classifier**
* Inputs:

  * Temperature
  * Humidity
  * Pressure
  * Wind Speed
  * Wind Direction

### 🌡 Temperature Prediction Model

* Algorithm: **Random Forest Regressor**
* Uses historical weather data to predict future temperature.

### 💧 Humidity Prediction Model

* Algorithm: **Random Forest Regressor**
* Predicts future humidity levels.

---

## 📈 Data Visualization

Temperature trends are visualized using **Chart.js**, allowing users to see predicted temperature changes over time.

---

## 🚀 Future Improvements

* 7-day weather forecast
* Deep learning models for weather prediction
* Interactive weather analytics dashboard
* Deployment on cloud platforms (Render / AWS / Heroku)

---

## 👩‍💻 Author

**Chethana Keshava Shettigar**

AI & Data Science Student
Passionate about **Machine Learning, Data Science, and Web Development**

---




