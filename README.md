# medical_recommendation_system
# 🏥 Medical Recommendation System (Flask + Machine Learning)

## 📌 Project Overview
This project is a **Symptom-Based Disease Prediction Web Application** developed using **Flask** and **Machine Learning (SVM model)**.  

The system allows users to enter their symptoms and predicts the most probable disease. It also provides additional medical information such as:
- Disease Description  
- Precautions  
- Medications  
- Diet Recommendations  
- Workout Suggestions  

This project demonstrates the integration of **Machine Learning with Web Development** to build a real-world healthcare support system.

---

## 🚀 Features

✔️ Symptom-based disease prediction  
✔️ Machine Learning model (Support Vector Machine)  
✔️ User-friendly web interface  
✔️ Detailed medical recommendations  
✔️ Multiple pages (Home, About, Contact, Blog, Developer)  
✔️ Speech recognition input (optional feature)

---

## 🧠 Machine Learning Model

- Algorithm Used: **Support Vector Classifier (SVC)**
- Input: Symptoms (binary encoded vector)
- Output: Predicted disease

### Model Workflow:
1. User enters symptoms  
2. Symptoms converted into binary vector  
3. Model predicts disease  
4. Disease mapped to name using dictionary  

---

## 🗂️ Project Structure
medical-project/
│
├── main.py # Flask backend
├── models/
│ └── svc.pkl # Trained ML model
│
├── datasets/
│ ├── symtoms_df.csv
│ ├── precautions_df.csv
│ ├── workout_df.csv
│ ├── description.csv
│ ├── medications.csv
│ ├── diets.csv
│
├── templates/
│ ├── index.html
│ ├── about.html
│ ├── contact.html
│ ├── developer.html
│ ├── blog.html
│
├── static/
│ └── img.png
│
└── README.md

---

## ⚙️ Technologies Used

- Python  
- Flask  
- Pandas  
- NumPy  
- Scikit-learn  
- HTML  
- CSS  
- Bootstrap

Example Input: 
itching, skin_rash, nodal_skin_eruptions
Output:
-Disease: Fungal Infection
-Description
-Precautions
-Medications
-Diet
-Workout

## Limitations
Depends on dataset quality
Cannot replace professional medical diagnosis
Sensitive to incorrect symptom input
Limited to predefined diseases

## Future Enhancement
-Add more diseases & symptoms
-Improve NLP-based symptom input
-Mobile app integration
-Cloud deployment
-User login & history tracking
-Real-time doctor consultation
