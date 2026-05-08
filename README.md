🌱 AgroSmart — Crop Recommendation System
AgroSmart is a machine learning–driven web application that recommends the most suitable crops based on soil nutrients and environmental conditions.

⚠️ This system is designed for decision support, not guaranteed predictions.

🚀 Live Demo
<p align="center">
  <a href="https://agrosmart-iota.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/🚀%20Launch%20AgroSmart-Live%20Demo-28a745?style=for-the-badge&logo=vercel" />
  </a>
</p>

🧠 Overview
Choosing the right crop is a multi-variable problem involving soil chemistry and climate factors. AgroSmart solves this by applying a trained ML model to provide data-driven crop recommendations in real time.

🛠 Tech Stack
Frontend: React (UI + data input)
Backend: Spring Boot (REST API, validation layer)
ML Service: Python (scikit-learn, pandas, NumPy)
Dataset: CSV-based agricultural dataset
⚙️ Features
Input parameters:

Nitrogen (N), Phosphorus (P), Potassium (K)
Temperature, Humidity
pH Level, Rainfall
Ranked crop recommendations

Input validation for realistic values

Clean and responsive UI

Modular architecture (Frontend ↔ Backend ↔ ML Service)

🔄 System Workflow
User inputs soil and climate data
React frontend sends request to backend
Spring Boot validates and forwards data
Python ML service processes input
Ranked crop results returned to user
📂 Project Structure
AgroSmart/
│── Frontend/        # React application
│── Backend/         # Spring Boot API
│── ML_Service/      # Python ML model
│── dataset/         # CSV dataset
🧪 Machine Learning Approach
Supervised learning model trained on agricultural dataset

Features used:

Soil nutrients (NPK)
Environmental conditions
Output: probability-based / ranked crop predictions

⚡ Setup Instructions
1️⃣ Frontend
cd Frontend
npm install
npm run dev
2️⃣ Backend
cd Backend
mvn spring-boot:run
3️⃣ ML Service
cd ML_Service
python -m venv .venv
.venv\Scripts\activate   # Windows
pip install -r requirements.txt
python crop.py
📌 Limitations
Dependent on dataset quality
No real-time weather integration
Does not consider pests, diseases, or market demand
🔮 Future Improvements
Real-time weather API integration
Fertilizer recommendation system
Scalable ML deployment (Docker / cloud)
Larger and more diverse dataset
👨‍💻 Author
Savan Patel
