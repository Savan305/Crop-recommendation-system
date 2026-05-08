🌱 AgroSmart — Crop Recommendation System

AgroSmart is a machine learning–driven web application that recommends the most suitable crops based on soil nutrients and environmental conditions.

⚠️ Disclaimer: This system is designed for decision support and educational purposes only. Recommendations are not guaranteed predictions.

🚀 Live Demo
<p align="center"> <a href="https://agrosmart-iota.vercel.app/" target="_blank"> <img src="https://img.shields.io/badge/🚀%20Launch%20AgroSmart-Live%20Demo-28a745?style=for-the-badge&logo=vercel" /> </a> </p>
📖 Overview

Choosing the right crop depends on multiple environmental and soil-related factors such as nutrient composition, temperature, humidity, rainfall, and pH level.

AgroSmart simplifies this process using a trained Machine Learning model that analyzes agricultural parameters and provides intelligent crop recommendations in real time.

The system follows a modular architecture:

Frontend → User Interface & Data Collection
Backend → API & Validation Layer
ML Service → Prediction Engine
🛠️ Tech Stack
Technology	Purpose
React	Frontend UI
Spring Boot	Backend REST API
Python	Machine Learning Service
scikit-learn	ML Model Training
pandas & NumPy	Data Processing
CSV Dataset	Agricultural Training Data
⚙️ Features
🌾 Crop Recommendation
Predicts suitable crops based on:
Nitrogen (N)
Phosphorus (P)
Potassium (K)
Temperature
Humidity
pH Level
Rainfall
📊 Ranked Predictions
Returns probability-based / ranked crop suggestions
✅ Input Validation
Prevents unrealistic or invalid values
🎨 Responsive UI
Clean and user-friendly interface
🧩 Modular Architecture
Independent frontend, backend, and ML services
🔄 System Workflow
User Input
    ↓
React Frontend
    ↓
Spring Boot Backend
    ↓
Python ML Service
    ↓
Prediction Generation
    ↓
Ranked Crop Recommendations
📂 Project Structure
AgroSmart/
│
├── Frontend/        # React application
├── Backend/         # Spring Boot REST API
├── ML_Service/      # Python ML model & prediction logic
├── dataset/         # Agricultural CSV dataset
└── README.md
🧠 Machine Learning Approach
📌 Model Type

Supervised Machine Learning

📌 Features Used
Soil Nutrients (NPK)
Temperature
Humidity
pH Level
Rainfall
📌 Output
Crop prediction
Ranked recommendation probabilities
⚡ Setup Instructions
1️⃣ Frontend Setup
cd Frontend
npm install
npm run dev
2️⃣ Backend Setup
cd Backend
mvn spring-boot:run
3️⃣ ML Service Setup
cd ML_Service

python -m venv .venv

# Activate Virtual Environment (Windows)
.venv\Scripts\activate

pip install -r requirements.txt

python crop.py
📌 Limitations
Dependent on dataset quality
No real-time weather integration
Does not consider:
Pests
Plant diseases
Market demand
Predictions may vary based on environmental changes
🔮 Future Improvements
🌦️ Real-time weather API integration
🌱 Fertilizer recommendation system
☁️ Docker & cloud deployment
📈 Larger and more diverse dataset
📱 Mobile-friendly optimization
👨‍💻 Author
Savan Patel
