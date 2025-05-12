
## 🌾 AgroTech – Crop Recommendation & Yield Prediction System

**AgroTech** is a machine learning-powered web application designed to assist farmers, agricultural planners, and government bodies in making informed decisions related to crop selection and yield forecasting. It combines predictive modeling with user-friendly design to promote sustainable and data-driven agriculture.

### 🔍 Features

* **Crop Recommendation**
  Suggests the most suitable crop for cultivation based on soil and environmental parameters like nitrogen (N), phosphorus (P), potassium (K), pH, temperature, humidity, and rainfall using the Random Forest algorithm.

* **Crop Yield Prediction**
  Estimates expected crop yield (in kg/hectare) using historical and environmental data such as year, pesticide usage, rainfall, temperature, crop type, and geographical area through a Decision Tree Regressor.

* **Web-Based Interface**
  A simple and accessible UI built using Flask, designed for ease of use by farmers, researchers, and policymakers.

### 📌 Technologies Used

* **Frontend:** HTML, CSS (inside `templates/`)
* **Backend:** Python (Flask), Pickle (`.pkl`) models
* **ML Models:** Random Forest (Crop Recommendation), Decision Tree Regressor (Yield Prediction)
* **Deployment:** Compatible with Render, Railway, or any cloud platform

---

