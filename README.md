#🥗NutriMate – Smart Diet Recommendation Web App
A project developed under the Summer Internship at IGDTUW (2025).
NutriMate is a lightweight, beginner-friendly diet recommendation system that blends a simple Machine Learning model with a clean HTML–CSS–JavaScript front end. The goal is to provide users with quick insights about suitable diet goals (Lose / Maintain / Gain) based on basic features like age, height, and weight.

Live Demo
Frontend: https://nutrimate10.netlify.app/
Backend (ML API): https://nutrimate-ml-1.onrender.com/
NutriMate is designed as a practical introduction to building an end-to-end ML-powered web application.

It demonstrates:
How a simple ML model can be trained using NumPy and Pandas
How to expose predictions through a Flask API
How a pure HTML/CSS/JS frontend can interact with a backend ML system
How to deploy both frontend & backend on free hosting services
This project helped in gaining hands-on experience in full-stack ML deployment, model building, API creation, and UI development.

Features
⭐ Interactive Web UI built using HTML, CSS, JavaScript
⭐ Lightweight ML Model trained using Linear Regression
⭐ API Endpoint /predict that returns prediction as JSON
⭐ Trained model stored as .pkl using joblib
⭐ Form-based input for Age, Height, Weight, Goal
⭐ Deployed on Netlify (Frontend) & Render (Backend)
⭐ Clean folder structure and modular code

Tech Stack
Frontend
HTML
CSS
JavaScript

Backend
Python
Flask
NumPy
Pandas
Scikit-Learn
Joblib

Deployment
Netlify (Frontend)
Render (Backend)

Folder Structure (Ideal GitHub Repo)
NutriMate/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│
├── backend/
│   ├── app.py
│   ├── train_model.py
│   ├── diet_model.pkl
│   ├── requirements.txt
│   ├── Procfile
│
├── README.md

🔧 How It Works
User enters age, height, weight
Frontend sends data to Flask backend
ML model processes input & predicts the diet goal
Response is returned in JSON format
Result is displayed on the UI
