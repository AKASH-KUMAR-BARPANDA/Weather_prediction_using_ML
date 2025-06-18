# 🌦️ Weather Prediction for Agricultural Decision Support

## 🎯 AIM OF THE PROJECT

To develop a machine learning model that predicts weather conditions (sun, rain, fog, snow, drizzle) based on historical weather data (including date, temperature, precipitation, wind speed) to help farmers make informed decisions about **planting, watering**, and **crop protection**.

---

## 🧠 UNIQUENESS / DIFFERENTIATOR TRIED OUT IN THE PROJECT

- Used **real-time weather categories** to suggest practical **crop actions** like:
  - 🌱 Planting when it's sunny
  - 💧 Watering when it's rainy
  - 🛡️ Protection when it's foggy, snowy, or drizzling
- Implemented a **Random Forest Classifier** to handle multiple classes tabular data.
- Created an intelligent mapping between predicted weather and agriculture decisions.

---

## 📌 INFERENCE

- The model performed well on weather prediction with a high overall accuracy of **85.32%**.
- However, precision and recall indicate the model favors frequent weather types, prompting possible future improvements using SMOTE or advanced ensemble models.
- The mapping from predicted weather to actionable crop advice ensures this system is not just analytical but **agriculturally useful**.

---

## 📊 METRICS OF THE PROJECT

| Metric      | Value    |
|-------------|----------|
| Accuracy    | 85.32%   |
| Precision   | 77.19%   |
| Recall      | 54.64%   |
| F1 Score    | 56.21%   |

> Note: Metrics computed using a test dataset with stratified splitting and macro-averaging due to class imbalance.

---

## 📈 FUTURE IMPROVEMENTS

- Use **SMOTE oversampling** to improve recall of minority weather classes like fog and snow.
- Deploy a simple **Flask web interface** for farmers to input current weather features and get crop recommendations.
- Integrate **live weather APIs** for real-time usage.

---

## 👨‍🌾 AGRICULTURAL ACTIONS BASED ON WEATHER PREDICTIONS

| Predicted Weather | Recommended Crop Action     |
|--------------------|-----------------------------|
| Sun                | 🌱 Good for planting         |
| Rain               | 💧 Good for watering         |
| Fog / Snow / Drizzle | 🛡️ Suggest crop protection |

---
